
# Content

Setting password is very important, especially when you have so many "interesting'' things in `F:\TDDOWNLOAD`.

We define the safety of a password by a value. First, we find all the substrings of the password. Then we calculate the maximum length of those substrings which, at the meantime, is a palindrome. 

A palindrome is a string that will be the same when writing backwards. For example, `aba`, `abba`, `abcba` are all palindromes, but `abcab`, `abab` are not.

A substring of $S$ is a continous string cut from $S$. `bcd`, `cd` are the substrings of `abcde`, but `acd`, `ce` are not. Note that `abcde` is also the substring of `abcde`.

The smaller the value is, the safer the password will be.

You want to set your password using the first $M$ letters from the alphabet, and its 
length should be $N$. Output a password with the smallest value. If there are multiple 
solutions, output the lexicographically smallest one.

All the letters are lowercase.

# Standard Input

The first line has a number $T$ ($T\leq 15$) , indicating the number of test cases.

For each test case, there is a single line with two integers $M$ and $N$, as described above. ($1 \leq M \leq 26$, $1 \leq N \leq 10^5$)

# Standard Output

For test case $X$, output `Case #X:` first, then output the best password.

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
2 2
2 3</td><td>Case #1: ab
Case #2: aab</td></tr></table>


# Constraints



# Note



# Source


