
# Content

Hongshu was awarded the title “The Outstanding Student of UESTC”(成电杰出学生). Hearing this pleasing news, SZX sensei was strucked by a nice problem for the enjoying game(趣味赛).

The aniki from School of Electronic Engineering gives SZX sensei a set of chips(芯片). SZX sensei wants to use some of these chips which can work together. Sensei find that a chip can be described by a matrix and the performance of it equals the matrix's row $\times$ matrix's column if measured in some particular unit. What's more, when the chips work together, the performance is the product(乘积) of the matrixes in the order the chips formed. That also means if the two matrixes which describe the two chips are able to multiple, the chips can work together. 

Now given the information of the chips, SZX sensei wants to know the best performance which these chips can reach.

# Standard Input

There will be a single number $T$ in the first line of the input, indicating the number of cases.In each test case there will be a number $n$($n\leq 10$) in the first line, and the each of the next $n$ lines has two number indicating the $row$($\leq 20$) and $column$($\leq 20$) of the matrix describing each chip.

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, output the best performance for each test case.

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
5
1 10
10 2
2 3
3 5
5 1
2
2 10
10 1</td><td>Case #1: 100
Case #2: 20</td></tr></table>


# Constraints



# Note

Sample 1:SZX sensei uses $5$ chips in the order `2 3 4 5 1`.

Sample 2:SZX sensei only uses the first chip.

# Source


