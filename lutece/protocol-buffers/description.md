
# Content

Protocol Buffers are a way of encoding structured data in an efficient yet extensible format. Google uses Protocol Buffers for almost all of its internal RPC protocols and file formats. In this problem, you will use a **simplified version** of protocol buffers.

####Message definition:
In protocol buffers, we defining a message in a very simple way:
```
message Gao {
  required int32 a = 1;
  required int32 b = 2;
  required string str = 3;
  repeated int32 arr = 4;
  optional int32 optionalField = 5;
}
```
The `Gao` message definition specifies five fields (name/value pairs), one for each piece of data that you want to include in this type of message. In this problem, there are at most $15$ fields in one message definition.

####Field definition:
Foremost, we need specifying field rules in one of the following:
  1. `required`: message must have **exactly one** of this field.
  2. `optional`: message can have **zero or one** of this field (but not more than one).
  3. `repeated`: this field can be repeated any number of times (**including zero**) in message. The order of the repeated values will be preserved.

Follow by the field rules, we definite field by type and name. we support `int32` and `string` type in this problem. Each field has assigned a unique numbered tag at the end. These tags are used to identify your fields in the message binary format. The smallest tag number is $1$, and the largest is $15$. Field name is consist of letters(`a`-`z` and `A`-`Z`) and do not exceed $15$ characters.

####Base 128 Varints:
To understand your simple protocol buffer encoding, you first need to understand varints. Varints are a method of serializing integers using one or more bytes. Smaller numbers take a smaller number of bytes. Each byte in a varint, except the last byte, has the **most significant bit (msb)** set –– this indicates that there are further bytes to come. The lower $7$ bits of each byte are used to store the two's complement representation of the number in groups of $7$ bits, **least significant group first**.
So, for example, here is the number $1$ –– it's a single byte, so the msb is not set:
```
0000 0001
```
And here is $300$ – this is a bit more complicated:
```
1010 1100 0000 0010
```
How do you figure out that this is $300$? First you drop the msb from each byte, as this is just there to tell us whether we've reached the end of the number (as you can see, it's set in the first byte as there is more than one byte in the varint):
```
1010 1100 0000 0010
→ 010 1100  000 0010
```
You reverse the two groups of $7$ bits because, as you remember, varints store numbers with the least significant group first. Then you concatenate them to get your final value:
```
000 0010  010 1100
→  000 0010 ++ 010 1100
→  100101100
→  256 + 32 + 8 + 4 = 300
```
(`++` means byte concatenation)

It's more complex to consider signed number, due to simplify this problem, we only need considered unsigned integers in range $[0, 10^9]$.

####Message structure:
As you know, a protocol buffer message is a series of key-value pairs. The binary version of a message just uses the field's tag number as the key –– the name and declared type for each field can only be determined on the decoding end by referencing the message type's definition. The "key" for each pair in a wire-format message is actually two values – the field tag number from your message definition, plus a wire type that provides just enough information to find the length of the following value.

The available wire types are as follows:
<table style="border:solid 1px">
<thead>
<tr>
<th style="border:solid 1px">Type</th>
<th style="border:solid 1px">Meaning</th>
<th style="border:solid 1px">Used for</th>
</tr>
</thead>
<tbody>
<tr>
<td style="border:solid 1px">0</td>
<td style="border:solid 1px">Varint</td>
<td style="border:solid 1px">int32</td>
</tr>
<tr>
<td style="border:solid 1px">2</td>
<td style="border:solid 1px">Length-delimited</td>
<td style="border:solid 1px">string,repeated fields</td>
</tr>
</tbody>
</table>

Each key in the streamed message is a varint with the value `(field_tag_number << 3) | wire_type` –– in other words, the last three bits of the number store the wire type. For example, key of field a in message `Gao` is encoded as `0000 1000(08)`, and for field `str` is `0001 1010(1A)`. Field `a` with value $150$ will be encoded as `08 96 01` (Key is `08` and $150$ encoded as `96 01`). Concatenate all encoded fields we can get the encoded message.

####Optional Elements:
If any of fields are optional, the encoded message may not have a key-value pair with that field, in this situation, just set the value of this field as `null`.

####String and Repeated Elements:
In this situation, we need specify payload size (varint type) first after key, and followed by the elements. (We can regard string type as a array)

For example:
```
message Test3 {
  required string b = 2;
  repeated int32 c = 3;
}
```
Assume one message have the value `testing` for field `b` and values $3$, $270$, and $86942$ for repeated field `c`, then, the encoded form would be:
```
12                    // tag (field number 2, wire type 2)
07                    // payload size (7 bytes)
74 65 73 74 69 6E 67  // ascii code of "testing"
1A                    // tag (field number 3, wire type 2)
06                    // payload size (6 bytes)
03                    // first element (varint 3)
8E 02                 // second element (varint 270)
9E A7 05              // third element (varint 86942)
```
Notice, repeated string type in this problem is illegal.

If any of repeated fields not appeared in this message, this field can regard as empty array(`[]`).

The length of arrays and strings will not exceed $50$ and strings only consist of alphabet(`a` - `z` and `A` - `Z`).

####Problem:
Now give you a message definition, and several encoded messages, you task is decode this messages.

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 10$).

For each case, there will be two integers $n$ ($n\leq 17$) and $m$ ($m\leq 100$).

The next $n$ lines consist of message definition, you can assume that the length of message definition will not exceed $1500$. A valid definition will only contains alphabet(`a` - `z` and `A` - `Z`), number(`0` - `9`), white space(` `) and control tokens(`=;{}`).

And then followed by $m$ queries, each line contain one encoded byte stream in hexadecimal notation, there is one white space after each byte. And for there are at most $1500$ bytes each message. Notice there will be some empty byte stream in test data, see sample input for more details.

All the messages in this problem will not contains unknown tags and have a illegal structure.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$).

Then for each query, output the values in each fields, with the same order in message definition.

If any of required fields not appeared in this message, please print `Error!` instead.

Output a blank line after each query.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1
2 5
message Test1{required int32 a=1;required string b=2
;repeated int32 c=3;optional int32 optionalField=5;}
08 96 01 12 07 74 65 73 74 69 6e 67 1A 06 03 8E 02 9E A7 05 28 00
08 96 01 12 07 74 65 73 74 69 6e 67 1A 06 03 8E 02 9E A7 05

08 96 01 12 01 74
12 07 74 65 73 74 69 6e 67 1A 06 03 8E 02 9E A7 05</td><td>Case #1:
a = 150
b = "testing"
c = [3, 270, 86942]
optionalField = 0

a = 150
b = "testing"
c = [3, 270, 86942]
optionalField = null

Error!

a = 150
b = "t"
c = []
optionalField = null

Error!</td></tr></table>


# Constraints



# Note



# Source


