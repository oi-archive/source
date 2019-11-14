
# Content

Given a matrix only consisting `0` and `1`. In this problem you should find the difference of two given sub-matrix.

# Standard Input

The first line of the input contains two integers $H,W$($1\leq H,W \leq 1000$), the height and width of the matrix. 

Then $H$ lines follows, each contains a string $S_i$($|S_i|=W$), representing the $i^{th}$ row of the matrix. $S_i$ contains only `0` and `1`.

The next line contains number of query $Q$ ($Q\leq 10^5$).

Each question contains eight integers $l_1$,$r_1$,$l_2$,$r_2$,$l_3$,$r_3$,$l_4$,$r_4$ 

($0\leq l_i <H,0 \leq r_i <W,l_1\leq l_2,r_1\leq r_2,l_3\leq l_4,r_3\leq r_4,l_2-l_1+1=l_4-l_3+1,r_2-r_1+1=r_4-r_3+1$), denote the top-left point and bottom-right point of the first and second sub-matrix.

# Standard Output

For each query output one line which means the answer.

If they are the same sub-rectangle, print the word `Perfect`

If they are different in one cell, print the sentence `One difference`

Otherwise print the word `Wrong` on a single line.

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
<tr><td>3 4
0011
0010
0000
1
0 0 1 2 1 0 2 2</td><td>One difference</td></tr></table>


# Constraints



# Note



# Source


