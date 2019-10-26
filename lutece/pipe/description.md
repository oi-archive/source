
# Content

The GX Light Pipeline Company started to prepare bent pipes for the new transgalactic light pipeline. During the design phase of the new pipe shape the company ran into the problem of determining how far the light can reach inside each component of the pipe. Note that the material which the pipe is made from is not transparent and not light reflecting.

![title](/source/lutece/pipe/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjM2LzIwMTQwMzE4MTQyNzU4NDcwMTIuZ2lm.gif)

Each pipe component consists of many straight pipes connected tightly together. For the programming purposes, the company developed the description of each component as a sequence of points $[x\_1,y\_1], [x\_2,y\_2], \cdots, [x\_n,y\_n]$ where $x\_1 < x\_2 < \cdots x\_n$ . These are the upper points of the pipe contour. The bottom points of the pipe contour consist of points with $y$-coordinate decreased by $1$. To each upper point $[x\_i, y\_i]$ there is a corresponding bottom point $[x\_i, (y\_i)-1]$ (see picture above). The company wants to find, for each pipe component, the point with maximal $x$-coordinate that the light will reach. The light is emitted by a segment source with endpoints $[x\_1, (y\_1)-1]$ and $[x\_1,y\_1]$ (endpoints are emitting light too). Assume that the light is not bent at the pipe bent points and the bent points do not stop the light beam.

# Standard Input

The input file contains several blocks each describing one pipe component. Each block starts with the number of bent points $2 \leq n \leq 40000$ on separate line. Each of the next $n$ lines contains a pair of real values $x\_i, y\_i$ separated by space. The last block is denoted with $n = 0$. The third line contains $N$ integers. Each one represents an ACMersTimes. $[1, 1000]$.

# Standard Output

The output file contains lines corresponding to blocks in input file. To each block in the input file there is one line in the output file. Each such line contains either a real value, written with precision of two decimal places, or the message Through all the pipe.. The real value is the desired maximal $x$-coordinate of the point where the light can reach from the source for corresponding pipe component. If this value equals to $x\_n$, then the message Through all the pipe. will appear in the output file.

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
<tr><td>4
0 1
2 2
4 1
6 4
6
0 1
2 -0.6
5 -4.45
7 -5.57
12 -10.8
17 -16.55
0</td><td>4.67
Through all the pipe.</td></tr></table>


# Constraints



# Note



# Source


