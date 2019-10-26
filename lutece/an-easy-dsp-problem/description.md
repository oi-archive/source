
# Content

Brother HeZai is a good student, he is good at $Digital$ $Signal$ $Processing$$(数字信号处理)$! He thinks any problem can be solved by $DFT(离散傅里叶变换)$,but you don’t think so and you give Brother HeZai an “easy”   problem.

Problem’s contents are as follows.

$Fast$ $Fourier$ $Transformation$$(快速傅里叶变换)$ is an algorithm used to calculate $convolution(卷积)$. Specifically, if $a$, $b$ and $c$ are sequences with length $N$, which are indexed from $0$ to $N - 1$

![title](/source/lutece/an-easy-dsp-problem/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM5My8yMDE2MDUyNTE4MDAyOTMyMDYxLnBuZw==.png)

And we can calculate c fast using Fast Fourier Transformation.

You made a little change on this formula. Now

![title](/source/lutece/an-easy-dsp-problem/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM5My8yMDE2MDUyNTE3NTk0MjI3MjYwLnBuZw==.png)

To make things easier, a is a permutation of integers from $1$ to $N$, and $b$ is a sequence only containing $0$ and $1$. Given $a$ and $b$, Brother HeZai needs to calculate $c$.

Brother HeZai is so powerful! He solves it immediately! But now it’s your turn, can you solve it?

# Standard Input

The first line only contains an positive integer $T$ ( $T \leq 22$ ) , represents there are $T$ test cases.

For each test case:

The first line contain one integer $N$, indicating the length of $a$. $1 \leq N \leq 5*10^4$

The next line contains a permutation from $1$ to $N$, indicating the elements of $a$.

The next line contains a 0-1 sequence of length $N$, indicating the elements of $b$.

# Standard Output

For each test case, output the element of $c$ in $N$ line.

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
3
1 3 2
1 0 0
5
2 1 4 5 3
1 1 1 0 1
</td><td>1
3
2
2
2
4
5
5
</td></tr></table>


# Constraints



# Note

![title](/source/lutece/an-easy-dsp-problem/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM5My8yMDE2MDUyNTE4MDM0ODAzMjYyLnBuZw==.png)

$Most$ $test$ $data$ $are$ $created$ $randomly$

# Source


