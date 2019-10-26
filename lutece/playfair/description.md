
# Content

Playfair is a kind of substitution cipher.And the encryption role is simple.In general,there are three steps in Playfair algorithm.

Step 1: Creat a 5*5 secret key table.

Step 2:Tidy plaintext : only leave letters and omit others And if there are capital letters in the plaintext,change it into lower letters. 

Step 3: Work out the ciphertext.

Now, let’s see an example.

Firstly,we should creat a 5*5 secret key table.Let’s assume that “ulysses” is the key.If there is a letter appearing more than once we should only retain the first one and delete the others.So we can get the real key “ulyse”.Then we will fill the secret key table with the key “ulyse” and with the other letters which haven’t appeared in the key “ulyse” in order(assume j is equal to i,so every element in the table is unique and j won’t be in this table).Finally, we will get a secret key table as follows:

<center>![title](/source/lutece/playfair/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTI3MC8yMDE1MTIxNzE4MDUzMjQ5NzkucG5n.png)</center>

Secondly,assuming that we will send a important message “balloon”.We should divide ballon into a few groups with exactly two letters.But if the two letters are the same,a single x will be inserted between the same two letters.So “balloon” will be divided into “ba” “lx” “lo” “on”.

Finally,we will encrypt the message.The substitution rules are followed:

1.If the group’s two letters are in the same row in the key table,each letter will be changed into the letter which is just on the right of it.(the first column is seen as on the right of the fifth column).

2.If the group’s two letters are in the same column in the key table,each letter will be changed into the letter which is adjacently below it.(the first row is seen as adjacent below fifth column).

3.If the group’s two letters are neither in the same row nor in the same column in the key table,each letter will be changed into the letter whose position is the same row as itself and the same column as another letter.

So “balloon” will be changed into “cbsvbvpo”.

Ps: j in the plaintext is equal to i and all the letter both in plaintext and ciphertext should be lower letter.And if there are capital letters in the plaintext,change it into lower letters.

# Standard Input

The first line will contain the secret key(no more than $25$ letters). Then you will get a article(including capital letter and the lower letter).You should omit all the spacing , the punctuation and the numbers(maybe has two or more rows).If there are odd letters after tidying plaintext,delete the last letter.The article would end with a ‘*’.

Ps:You can assume that the article is no more than $10000$ letters.And “xx” won’t exist. And the secret key only contains lower letters.

# Standard Output

The ciphertext which only includes lower letters.

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
<tr><td>cipher
balloon
*</td><td>dbspgsug</td></tr><tr><td>cipher
fill book*</td><td>aespslsvqg
</td></tr></table>


# Constraints



# Note



# Source


