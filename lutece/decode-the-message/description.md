
# Content

Two of your friends Alex and Adam have developed a secret system for sending messages to each other. The only problem is that the system has turned out to be too hard to do by hand. Therefore, Alex has asked for your help to write a program to decode the secret messages. After making you swear never to reveal the system, he explains that the coded message consists of one or more words, only consisting of lower case characters `a`-`z`, seperated by spaces. Each word corresponds to one character, `a`-`z` or space, and is found by adding the value of each character in the word and taking the remainder when dividing by $27$. `a` is assigned the value $0$, `b` is assigned the value $1$ and so on up to `z` which is assigned the value $25$. Based on the calculated remainder the values $0-25$ corresponds to `a`-`z` as before, and the value $26$ corresponds to a space.

Help your friend write a program which takes a coded message and outputs the decoded message.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each test case consists of a single line containing a secret message. The secret message contains only lower case characters and spaces, and there are only spaces between words and never two or more consecutive spaces.

# Standard Output

For each test case, output the corresponding decoded message.

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
a b c d e f
it is late o green wrong whole</td><td>abcdef
a horse</td></tr></table>


# Constraints



# Note

$0 < T \leq 100$

Each secret message contains no more than $1000$ characters

# Source


