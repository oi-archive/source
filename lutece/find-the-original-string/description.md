
# Content

Zplinti1 forgot his password. He is very depressed, since it is very important.

Luckily, he remembers the time when he set his password. He thought of a string that seemed beautiful, then he shifted this string again and again and wrote each shifted string on different papers.

Here, a `shifting` means to remove the first character in the string and put it at the back. For example, a single shifting for string `abcde` is `bcdea`, then `cdeab`, and so on. 

Zplinti1 had written down all the possible strings after shifting, including the original string. He never wrote a same string twice. Then he connected all the written strings into a final string in any order. Each string is used exactly once. 

Given the final string zplinti1 got, help him find the shortest possible password, if there are multiple such solutions, output the one with the smallest lexicographically order.

# Standard Input

The first line of input contains a number $T$($T\leq 20$), indicating the number of test cases. 

For each case, there is a string $s$($|s|\leq 100,000$), which is the string zplinti1 wrote down. **All the strings contains lowercase letters from `a` to `z` only**.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the possible password, if there are no solutions, output `Impossible`.

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
abccabbca
abba
abab</td><td>Case #1: abc
Case #2: ab
Case #3: Impossible</td></tr></table>


# Constraints



# Note



# Source


