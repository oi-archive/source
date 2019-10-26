
# Content

You have such a string $S$ `a`, every time you can copy $S$ to $T$ ,change `a` in $T$ to `b`, `b` to `a`, then add $T$ after $S$.

For example,

`a`

`ab`

`abba`

`abbabaab`

`abbabaabbaababba`

`......`

Finally you will get a infinite magic string.

Now, given a string $X$ only containing `a` and `b`, you should tell me if it appears in the magic string?

If it appears, than output the location it first appears, otherwise, output `-1`;

# Standard Input

A line with a string that consists only `a` and `b` and no more than $10^6$ characters.

# Standard Output

Print the position of the first occurrence of the string, or `-1` if it doesn't exist.

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
<tr><td>bab</td><td>3</td></tr><tr><td>baab</td><td>5</td></tr><tr><td>aaabbb</td><td>-1</td></tr></table>


# Constraints



# Note



# Source


