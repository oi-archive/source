
# Content

读入三角形三边的边长$a,b,c$，输出它的面积。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 1000$），表示测试数据的组数。每一组测试数据只有一行，分别为边长$a$、$b$和$c$，三数之间有一个空格。该行没有其它多余的符号。$a,b,c$均为正整数，其大小不超过$10^6$。

# Standard Output

对应每组输入，输出一行该三角形的面积，保留两位小数。如果三条边不能构成三角形，请输出`can't construct a triangle!`。该行不能有其它多余的符号。输出格式具体见样例。

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
3 4 5
3 4 7
3 4 8</td><td>S(3,4,5)=6.00
S(3,4,7)=0.00
(3,4,8) can't construct a triangle!</td></tr></table>


# Constraints



# Note

可以使用公式：$S=\sqrt{p(p-a)(p-b)(p-c)}$，其中$p=\frac{a+b+c}{2}$。

# Source


