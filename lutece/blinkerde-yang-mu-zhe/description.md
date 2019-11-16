
# Content

`Blinker`有非常多的仰慕者，他给每个仰慕者一个正整数编号。而且这些编号还隐藏着特殊的意义，即编号的各位数字之积表示这名仰慕者对`Blinker`的重要度。

现在`Blinker`想知道编号介于某两个值$A$,$B$之间，且重要度为某个定值$K$的仰慕者`编号和`。


# Standard Input

输入的第一行是一个整数$N$，表示`Blinker`想知道的信息个数。 
接下来的$N$行，每行有三个数，$A$,$B$,$K$。表示`Blinker`想知道编号介于$A$和$B$之间的，重要度为$K$的仰慕者的编号和。

$2\leq A\leq B\leq 1000000000000000000$,$1\leq N\leq 5000$。 

# Standard Output

输出$N$行，每行输出介于$A$和$B$之间，重要度为$K$的仰慕者编号和。结果可能很大，模上$20120427$。

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
1 14 4 
1 30 4 
10 60 5</td><td>18 
40 
66</td></tr></table>


# Constraints



# Note

第一组样例中，在$1$到$14$之间各位数字之积等于$4$的有$4$和$14$，故编号和为$18$。

# Source


