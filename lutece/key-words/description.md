
# Content

Given the target string $T$, find all the palindromes which could have generated $T$.

The generated way was:

Start with an empty string $S$.

Suppose string $P$ is a `palindrome`.

Then, choose some position in the string (maybe the very beginning or the very end) and insert $P$.

Try to do it again and again until you reach the target string.

For example, $P$ is `aba`, after a single step, $S$ becomes `aba`.

Now Insert $P$ into $S$ again, $S$ may become `a aba ba`.

If `aababa` is the target string, then `aba` is a possible solution.

# Standard Input

Only one line contains a nonempty target string $T$ $(|T| \le 200)$, containing only `a` to `z`.

# Standard Output

Output all the possible solution in lexicographical order.

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
<tr><td>aababa</td><td>aba</td></tr><tr><td>aaa</td><td>a
aaa</td></tr></table>


# Constraints



# Note



# Source


