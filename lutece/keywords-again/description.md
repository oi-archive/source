
# Content

Do you like the Problem K in Preliminary Contest? Now, this is another Keywords Problem.

Given a generated way:

Start with an empty string $S$. Then, choose some position in the string (maybe the very beginning or the very end) and insert $P$. We will get a new $S$ and try to insert it again and again.

For example, $P$ is `abc` and $S$ is empty, after a single step, $S$ becomes `abc`. Now Insert $P$ into $S$ again, $S$ may become `aabcbc`.

Now show you a string $Q$, can you tell me if there exists a string $T$ generated as we mentioned above, and $Q$ is the substring of $T$.

# Standard Input

The first line contains a non-empty string $P$.

The second line contains a non-empty string $Q$.

Both $P$ and $Q$ will only contains `a` to `z`

$1\leq |Q|\leq |P|\leq 10^5$

# Standard Output

If there exists a string $T$ generated as we mentioned above, and $Q$ is the substring of $T$, output `POSSIBLE`, otherwise output `IMPOSSIBLE`.

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
<tr><td>abcde
bcaab</td><td>POSSIBLE</td></tr><tr><td>abcde
eabde</td><td>IMPOSSIBLE</td></tr></table>


# Constraints



# Note



# Source


