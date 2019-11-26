
# Content

### define
定义一种新的运算'$*$'.

'$*$'运算满足对于任意的两个数$x, y$, 都有:

![a](/source/lutece/suan-shu-di-shou/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTg0Ny8yMDE4MDMwMzE1MDEzNTMxMTguanBlZw==.jpeg)

'$*$'运算也满足结合率.
***

### define
定义一种'字句'$w$, 满足后面关系: 

$w = a * (w')$ 或 $w = (w') * a$ 或 $w = a * b$

(其中的$a$和$b$可以为任意变量('a' - 'z'))

举例: $w = d*(((a*b)*a)*c)$
***

### Task
给出一个由加法和'字句'组成的等式, 问等式是否是恒成立的.

等式的形式如下:

![b](/source/lutece/suan-shu-di-shou/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTg0Ny8yMDE4MDMwMzE1MDQzNjI5MjkuanBlZw==.jpeg)

# Standard Input

一行, 表示题目中给出的等式, 等式中的变量只会是'a'-'z'的26个小写字母

# Standard Output

一行, 等式恒成立输出'True'(不要引号), 否则输出'False'(不要引号)'

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
<tr><td>(a * b) * b = b * (b * a)</td><td>True</td></tr></table>


# Constraints



# Note



# Source


