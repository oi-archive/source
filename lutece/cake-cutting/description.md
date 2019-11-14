
# Content

Today is Simon's birthday, he receives a birthday cake. This cake is a rectangle with its length is $N$ and width is $M$, And Simon cut $K$ times. Now, he want you to tell him this cake has been divided into how many parts, and the area of each part.

To simplify this problem, we put this cake on a $2$-Dimension rectangular coordinate system, and the edge of cake is parallel to the axes. And the lower left corner is at $(0,0)$, the upper right corner is at $(N,M)$. Each time of cutting will be parallel to the axis, the starting point and the ending point will be integral points. 

P.S. We call a point $(X,Y)$ as a integral point if and only if $X$ and $Y$ are both integers.

# Standard Input

First line of the input is a single integer $T$($T\leq 30$), indicates there are $T$ test cases.

For each test case, the first line is three integers $N$($1\leq N\leq 500$), $M$($1\leq M\leq 500$) and $K$($1\leq K\leq 1000$), the length and the width of the cake, how many times Simon has cut.

Then $K$ lines followed, the $i\_{th}$ line contains four integers $s\_x,s\_y,e\_x,e\_y$($-10^9<s\_x,s\_y,e\_x,e\_y\leq 10^9$), means the start point and the end point, data will ensure that $s\_x=e\_x$ or $s\_y=e\_y$. Notice that the starting point or the ending point will not necessary on the cake exactly.

# Standard Output

For each case, you should output two lines.

First line,`Case #k: n`, where $k$ indicates the case number between $1$ and $T$, $n$ means the cake has been divided into how many parts.

Second line should contain $n$ integers $a\_1,a\_2,\cdots ,a\_{n-1},a\_n$, where $a\_i$ means the $i\_{th}$ part's area, and $a\_i\leq a\_{i+1}$ for $1\leq i\leq n-1$.

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
2 2 2
0 1 2 1
1 0 1 2
2 2 2
0 1 2 1
1 0 1 1
2 2 1
1 -3 1 1</td><td>Case #1: 4
1 1 1 1
Case #2: 3
1 1 2
Case #3: 1
4</td></tr></table>


# Constraints



# Note



# Source


