
# Content

Mr. Cooper was a celebrated scientist who had a really big lab. There were $N$ sticks in this lab and the length of the $i\_{th}$ stick was $i$ millimeters. One day, when Mr. Cooper decided to do research on triangles, he found that $M$ of the sticks were missed. Mr. Cooper wanted to know how many kinds of triangles could be constructed by three of the remaining sticks. Two triangles are different if and only if they are formed by different sets of sticks. 

For Example, there were $8$ sticks in the lab originally and the second and the sixth sticks were missed. The $7$ different triangles can be constructed were `3,4,5`, `3,5,7`, `4,5,7`, `3,7,8`, `4,7,8`, `5,7,8`, `4,5,8`.

# Standard Input

The first line contains an integer $T$ ($T\leq 25$) indicating the number of test cases. The first line of each test case contains two integers $N$ ($1\leq N\leq 1000000000$) and $M$ ($0\leq M\leq 1000$). If $M$ is not zero, there is an additional line containing $M$ distinct integers between $1$ and $N$ indicating the missed sticks.

# Standard Output

For each test case, print the case number and the answer mod $1000000007$ in a single line where the answer is the number of the triangles can be formed. Please follow the format of the sample output.

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
3 0 
8 2 
2 6 
58 3 
23 5 3</td><td>Case 1: 0 
Case 2: 7 
Case 3: 13861</td></tr></table>


# Constraints



# Note



# Source


