
# Content

There is a straight highway with villages alongside the highway. The highway is represented as an integer axis, and the position of each village is identified with a single integer coordinate. There are no two villages in the same position. The distance between two positions is the absolute value of the difference of their integer coordinates. 

Post offices will be built in some, but not necessarily all of the villages. A village and the post office in it have the same position. For building the post offices, their positions should be chosen so that the total sum of all distances between each village and its nearest post office is minimum. 

You are to write a program which, given the positions of the villages and the number of post offices, computes the least possible sum of all distances between each village and its nearest post office.

# Standard Input

Your program is to read from standard input. The first line contains two integers: the first is the number of villages $V$, and the second is the number of post offices $P, 1 \leq P \leq V \leq 1000$. The second line contains $V$ integers in increasing order. These $V$ integers are the positions of the villages. For each position $X$ it holds that $1 \leq X \leq 10000$.

# Standard Output

The first line contains one integer $S$, which is the sum of all distances between each village and its nearest post office.

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
<tr><td>10 5
1 2 3 6 7 9 11 22 44 50</td><td>9</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by StephYDX. So any mistake here does not imply mistake in the offcial judge data.

# Source


