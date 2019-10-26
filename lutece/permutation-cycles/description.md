
# Content

There are several ways to represent a permutation of the $n$ integers from $1$ to $n$. For example, when the permutation of $8$ integers is $(3,2,7,8,1,4,5,6)$, one way to represent it as an array is
\begin{cases}
\text{$1\   2\   3\   4\   5\   6\   7\   8$}\\\
\text{$3\   2\   7\   8\   1\   4\   5\   6$}\\\
\end{cases} 
Another way to represent it in cycle-arrow form is shown in Figure $1$.<img src="https://odzkskevi.qnssl.com/fd846196da8ef99c938cde687c3f4dfe?v=1516416308"  width = "400" />

If we represent a permutation as an array 
\begin{cases}
\text{$1…i…n$}\\\
\text{$π\_{1}…π\_{i}…π\_{n}$}\\\
\end{cases} 
then there is a directed edge from $i$ to $π\_{i}$ in its corresponding cycle-arrow form for each $i$.

As shown in Figure $1$, there are $3$ cycles when we represent permutation $(3,2,7,8,1,4,5,6)$ in cycle-arrow form. We call these cycles ‘permutation cycles.’

You are to write a program which counts the number of permuation cycles in a given permutation of $n$ integers.

# Standard Input

Your program is to read from standard input. The input consists of $T$ test cases. The number of test cases $T$ is given in the first line of the input. Each test case starts with a line containing an integer $n$ $(2 ≤ n ≤ 1,000)$. In the following line there is a permutation of $n$ integers from $1$ to $n$. Each integer in a permutation is separated by a blank.

# Standard Output

Your program is to write to standard output. Print exactly one line for each test case. The line should contain the number of permutation cycles in the given permutation.

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
8
3 2 7 8 1 4 5 6
10
2 1 3 4 5 6 7 9 10 8</td><td>3
7</td></tr></table>


# Constraints



# Note



# Source


