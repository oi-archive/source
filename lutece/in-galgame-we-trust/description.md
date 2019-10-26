
# Content

As we all know, there are many interesting (H) games in kennethsnow’s computer. But he sets a password for those games. Zplinti1 wants to crack his password and play those games.

Kennethsnow uses only $6$ kinds of characters to form his password: 

1.  brackets: `(` and `)`
2.  square brackets: `[` and `]`
3.  curly brackets: `{` and `}`

Kennethsnow’s password must be a correct bracket sequence, and will not be empty.

Zplinti1 found a string written by kennethsnow, and he is sure that kennethsnow’s password is a substring of that, he wonders the maximum possible length of his password, or if his judgment is wrong. 

**Please note that the original string may also be the password.**

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 30$)
For each case, there is a string s, which is the string zplinti1 found.
($1\leq |s|\leq 1,000,000$, the string will contain those $6$ kinds of characters only)

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). If zplinti1’s judgment is wrong (i.e. the answer is $0$), output `I think H is wrong!`, otherwise output a single number, indicating the maximum possible length of kennethsnow’s password.

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
<tr><td>3
(){[]}
{([(])}
))[{}]]</td><td>Case #1: 6
Case #2: I think H is wrong!
Case #3: 4</td></tr></table>


# Constraints



# Note

We can define a `correct bracket sequence` more precisely in this way:

Strings `()`, `[]`, and `{}` are correct.

For each correct sequence `A`, `(A)`, `[A]`, `{A}` is also correct.

For each correct sequence `A` and `B`, `AB` is also correct.

# Source


