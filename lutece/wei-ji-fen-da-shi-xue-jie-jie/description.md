
# Content

这是一道微积分题目！  
求椭圆

$$\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$$

在$x=L$和$x=R$之间的面积。

# Standard Input

输入$4$个小数表示$a,b,L,R$  
$1\le a,b \le 100$  
$-a\le L < R \le a$

# Standard Output

输出保留3位小数  
可以使用`double ans = 2.0; printf("%.3f\n", ans);`  
推荐使用double而非float

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
<tr><td>2 1 -2 2</td><td>6.283</td></tr><tr><td>2 1 0 2</td><td>3.142</td></tr></table>


# Constraints



# Note

可以使用math.h库  
含有asin,acos,atan,sin,cos,tan,log,log2,log10等函数

# Source


