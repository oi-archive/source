
# Content

Zplinti1 is given a big and long string $S$, together with a list of strings that are viruses. He wants to find the number of substrings of $S$, so that it does not contain any viruses. **Same substrings with different starting positions are regarded as different!**

Zplinti1 finds this problem difficult enough, he thinks `Only God Can Solve This Problem`, but you don’t think so, right?

# Standard Input

The first line of input contains a number $T$, indicating the number of cases. ($T\leq 30$)
For each case, the first line is a string $S$, with length no more than $1,000,000$. The second line is a number $n$, which is the number of virus strings. Then $n$ lines comes, each with a string. 

All the strings contains lowercase letters from `a` to `z` only. The total length of all virus strings in one case will be no more than $100,000$.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the number of substrings of $S$ that do not contain any virus.

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
aabc
0
aabbaa
1
a
abcdefg
2
bcd
ef</td><td>Case #1: 10
Case #2: 3
Case #3: 14</td></tr></table>


# Constraints



# Note

A substring of a string $S$ is a continuous string taken from $S$. For example if we take out the letters from the $L_{th}$ to the $R_{th}$ of the string, then the substring will be ($S_L, S_{L+1}\cdots S_R$). 

The original string is a substring of itself.

When we say string $A$ `contains` string $B$, it means that $B$ is a substring of $A$.

# Source


