
# Content

Darwin likes to write poetry about geometry. This is one of his most famous poetry: 

<i>
Lie on a plane</br>
Two rectangles and many line segments.</br>
</br>
Ah, gentle rectangles! All your sides parallel to X-axis or Y-axis.</br>
And one of you strictly encircles the other one</br>
Without any touch!</br>
The best place in the world</br>
The area between you two is.</br>
</br>
Stupid line segments!</br>
Why you run across my darling rectangles?</br>
I will try all I can</br>
to clear you off the best place. </br>
</i>

![title](/source/lutece/darwin/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTU4LzIwMTQwODI2MTMyNDI1MTc4MTcuanBn.jpg)

Darwin expressed his hatred towards line segments because they run into the area between the two rectangle (blue area in the above picture). **He wanted to clear segments in that area.** Given the rectangles and all the segments on the plane, please calculate the total length of segments Darwin needs to clear.

Note that segments are independent of each other, that is to say, Darwin has to clear the segments one by one even they may cover the same place. Segments coinciding with the boundaries of rectangles don't count into result.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 20$) indicating the number of test cases.

For each case, the first line contains eight integers: $P\_x$, $P\_y$, $L\_1$, $W\_1$, $Q\_x$, $Q\_y$, $L\_2$, $W\_2$. The lower left corner of the rectangle is at point $(P\_x, P\_y)$, its length on the $x$-axis is $L\_1$ and on the $y$-axis is $W\_1$. The lower left corner of the hole is at point $(Q\_x, Q\_y)$, with size of $L\_2 \times W\_2$.

An integer $N$ comes in the next line, which is the number of line segments. The following $N$ lines each with four integers give the line segments in this format: $S\_x$ $S\_y$ $T\_x$ $T\_y$, representing the two ends, $(S\_x,S\_y)$ and $(T\_x,T\_y)$, of each segments.

$1 \leq N \leq 10000$, $1 \leq L\_2 < L\_1 \leq 20000$, $1 \leq W\_2 < W\_1 \leq 20000$. All other numbers in the input would have absolute values no more than $10000$. For each segment, the two ends do not coincident.

# Standard Output

For each task, print `Case #t: L` in a single line, in which $t$ is the number of this case starting from $1$, and $L$ is the length Darwin needs to clear (rounded to two decimal place).

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
<tr><td>1
0 0 4 3 1 1 2 1
7
-1 0 1 0
0 1 2 3
1 3 1 -1
-1 4 1 4
2 0 4 3
2 1 4 1
4 0 2 2</td><td>Case #1: 10.25</td></tr></table>


# Constraints



# Note



# Source


