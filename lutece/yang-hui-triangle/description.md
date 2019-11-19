
# Content

Harry is a Junior middle student. He is very interested in the story told by his mathematics teacher about the Yang Hui triangle in the class yesterday. After class he wrote the following numbers to show the triangle our ancestor studied.

![title](/source/lutece/yang-hui-triangle/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjg3LzIwMTQwMzE5MDkxMzU5MDY5OC5qcGc=.jpg)

He found many interesting things in the above triangle. It is symmetrical, and the first and the last numbers on each line is $1$; there are exactly $i$ numbers on the line $i$.

Then Harry studied the elements on every line deeply. Of course, his study is comprehensive.

Now he wanted to count the number of elements which are the multiple of $3$ on each line. He found that the numbers of elements which are the multiple of $3$ on line $2, 3, 4, 5, 6, 7, \cdots $ are $0, 0, 2, 1, 0, 4, \cdots $ So the numbers of elements which are not divided by $3$ are $2, 3, 2, 4, 6, 3, \cdots ,$ respectively. But he also found that it was not an easy job to do so with the number of lines increasing. Furthermore, he is not satisfied with the research on the numbers divided only by $3$. So he asked you, an erudite expert, to offer him help. Your kind help would be highly appreciated by him.

Since the result may be very large and rather difficult to compute, you only need to tell Harry the last four digits of the result.

# Standard Input

There are multiple test cases in the input file. Each test case contains two numbers $P$ and $N, (P < 1000, N \leq 10^9)$, where $P$ is a prime number and $N$ is a positive decimal integer.

$P = 0, N = 0$ indicates the end of input file and should not be processed by your program.

# Standard Output

For each test case, output the last four digits of the number of elements on the $N + 1$ line on Yang Hui Triangle which can not be divided by $P$ in the format as indicated in the sample output.

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
3 48
0 0</td><td>Case 1: 0004
Case 2: 0012</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by GreenWall. So any mistake here does not imply mistake in the offcial judge data.

# Source


