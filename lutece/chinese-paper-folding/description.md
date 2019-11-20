
# Content

Chinese Paper Folding, or Zhezhi, is the art of folding paper that originated in China. It is the predecessor of origami.

Here we only consider a simplified problem. You are given a paper L cm by W cm in size and a list of operations to fold it.

Four types of operation are listed below: 
1. `L v` , fold the left part of paper along the straight line $x = v$.
2. `R v`, fold the right part of paper along the straight line $x = v$.
3. `U v`, fold the upper part of paper along the straight line $y = v$.
4. `D v`, fold the lower part of paper along the straight line $y = v$.

Note that v is always an integer.

![title](/source/lutece/chinese-paper-folding/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjkwLzIwMTQwNDA5MjAzMzMzMjE0MS5qcGc=.jpg)

We define the left-lower corner of current paper as $(0, 0)$ at every step (refer to the picture below). It is guaranteed that each operation is legal, that is, each operation is asked to fold paper of a positive area.

![title](/source/lutece/chinese-paper-folding/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjkwLzIwMTQwNDA5MjAzMzM4Nzg5Mi5qcGc=.jpg)

It is obvious that folding will make the straight lines into creases. We wonder the total length of all creases when paper is completely unfolded.

# Standard Input

In the first line there is an integer $T$, indicates the number of test cases. ($T\leq 50$)

For each case, the first line is a pair of integers $L$ and $W$ ($1\leq L, W\leq 1,000,000$), which stands for the length and width of the paper. In the second line, an integer $K$ stands for the number of operations. ($K\leq 100000$) Then $K$ lines follow, each stands for an operation described above.

# Standard Output

For each case, output `Case x: R` on a single line, in which $x$ is the case number counted from one, $R$ is the total length of all creases.

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
<tr><td>2
50 50
4
L 30
D 5
R 3
U 5
65536 1
16
L 32768
L 16384
R 8192
R 4096
L 2048
R 1024
L 512
R 256
R 128
L 64
R 32
R 16
L 8
R 4
L 2
R 1</td><td>Case 1: 250
Case 2: 65535</td></tr></table>


# Constraints



# Note



# Source


