
# Content

The GoldenEye satellite one day intercepted signals from some alien communication. It was found that the secret messages are encoded and being sent in form of digits only. It was also found that the digits are simple replacement for alphabetic characters. With some analysis, it was discovered that the encoding was done by converting alphabets $A$ to $1$, $B$ to $2$, $C$ to $3$ and so on till $Z$ to $26$.

Computational power at satellite is limited so we want to know first how many different representations of text can result in certain encoded message. E.g.: $127$ can be an encoding of $2$ different messages: “$ABG$” or “$LG$”. Similarly $123$ can be encoding of $3$ different messages: “$ABC$” or “$LC$” or “$AW$”.

Your task is to write a program, which takes encoded secret-message as input and calculates the maximum number of text combinations which can result in that secret message.

# Standard Input

The input consists of multiple test cases. The first line of input is the number of test cases $N$ $(1≤N≤100)$. Each of the following $N$ lines contains one string representing the secret messages (all numeric). Each string can be up to $100$ characters long.

# Standard Output

For each test case, print a single line that says "$Case$ #$n:$ " where $n$ is the test case number followed by a space and the maximum number of possible string combinations that can result in decoded secret-message for that test case.

It's guaranteed that the answer won't exceed $2^{64}-1$.

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
<tr><td>5
127
123
2222
30
345678934567893456789</td><td>Case #1: 2
Case #2: 3
Case #3: 5
Case #4: 0
Case #5: 1</td></tr></table>


# Constraints



# Note



# Source


