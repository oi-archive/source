
# Content

The new operating system BerOS has a nice feature. It is possible to use any number of characters `/` as a delimiter in path instead of one traditional `/`. For example, strings `//usr///local//nginx/sbin//` and `/usr/local/nginx///sbin` are equivalent. The character `/` (or some sequence of such characters) at the end of the path is required only in case of the path to the root directory, which can be represented as single character `/`.

A path called normalized if it contains the smallest possible number of characters `/`.

Your task is to transform a given path to the normalized form.

# Standard Input

There are multi-cases. The first line of each case contains only lowercase Latin letters and character `/` — the path to some directory. All paths start with at least one character `/`. The length of the given line is no more than $100$ characters, it is not empty.

# Standard Output

The path in normalized form.

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
<tr><td>//usr///local//nginx/sbin</td><td>/usr/local/nginx/sbin</td></tr></table>


# Constraints



# Note



# Source


