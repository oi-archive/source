
# Content

Dalong design a simple, easy to remember system for encoding integer amounts can be very useful. For example, dealers at flea markets put the information about an item on a card that they let potential buyers see. They find it advantageous to encode the amount they originally paid for the item on the card.

A good system is to use a substitution code, in which each digit is encoded by a letter. An easy to remember $10$-letter word or phrase, the key, is chosen. Every `1` in the value is replaced by the first letter of the key, every `2` is replaced by the second letter of the key, and so on. Every `0` is replaced by the last letter of the key. Letters that do not appear in the key can be inserted anywhere without affecting the value represented by the code.. This helps to make the resulting code much harder to break (without knowing the key).

Now give you a key and code, you task is calculate the decoded value.

# Standard Input

There are several test cases, first line is a positive integer $t$($1 \leq t \leq 20$), represent there are t test cases.

For each test case contain one line, two strings key and code. 

The key contains exactly $10$ uppercase letters `A`-`Z`, all distinct from each other

The code contains between $1$ and $9$ characters inclusive, all uppercase letters `A` - `Z`. There at least one letter that is found in key.

# Standard Output

For each case, output a integer, which is the decoded value.

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
<tr><td>2
TRADINGFEW LGXWEV
ABCDEFGHIJ XJ</td><td>709
0</td></tr></table>


# Constraints



# Note



# Source


