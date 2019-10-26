
# Content

Given a string S consisting of lower-case English letters only, your task is to find out if there is a substring which the number of '$a$','$b$'.. are $cnt_a,cnt_b,...$?

# Standard Input

The first line of the input contains a string $S$($1\leq |S| \leq 10^5$)

The next line contains $26$ integers $cnt_a,cnt_b...$ ($0\leq cnt_i\leq|S|$).

# Standard Output

If there is a substring meets the above conditions, print the word `Yes`

Otherwise print the word `No` on a single line.

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
0 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0</td><td>Yes</td></tr><tr><td>abcde
0 1 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0</td><td>No</td></tr></table>


# Constraints



# Note



# Source


