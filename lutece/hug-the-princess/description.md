
# Content

There is a sequence with $n$ elements. Assuming they are $a\_1, a\_2, \cdots , a\_n$.

Please calculate the following expession.

$\displaystyle{\sum_{1\leq i < j \leq n} (a\_i \wedge a\_j)+(a\_i | a\_j)+(a\_i \& a\_j)}$

In the expression above,  `^` `|` `&` is bit operation. If you don’t know bit operation, you can visit 

http://en.wikipedia.org/wiki/Bitwise_operation

to get some useful information.

# Standard Input

The first line contains a single integer $n$, which is the size of the sequence.

The second line contains $n$ integers, the $i\_{th}$ integer $a\_i$ is the $i\_{th}$ element of the sequence.

$1 \leq n \leq 100000, 0 \leq a\_i \leq 100000000$

# Standard Output

Print the answer in one line.

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
1 2</td><td>6</td></tr></table>


# Constraints



# Note

Because the answer is so large, please use long long instead of int. Correspondingly, please use `%lld` instead of `%d` to scanf and printf.

** Large input. You may get Time Limit Exceeded if you use "cin" to get the input. So "scanf" is suggested. **

** Likewise, you are supposed to use "printf" instead of "cout". **

# Source


