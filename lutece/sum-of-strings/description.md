
# Content

定义两个字符串$s\_1$和$s\_2$的和是这两个字符串首尾相连，比如给定两个字符串

$s\_1=$`AB`，$s\_2=$`CD`，它们的和$s\_1+s\_2=$`ABCD`。

根据以上定义，我们定义如下函数

$f(n)=\left\\{\begin{matrix}
a & (n=0)\\\\ 
b & (n=1)\\\\ 
f(n-2)+f(n-1) & (n>1) 
\end{matrix}\right.$

# Standard Input

第一行包含一个整数$T$，代表测试数据组数。($T\leq 100$)

接下来$T$行，每行包括两个字符串$a,b$和三个整数$n,i,j$ ($0\leq n\leq 10^8$, $0\leq i\leq j\leq 10^8$) ,输出$f(n)$中从$i$到$j$的一段子串，$a$和$b$的长度不超过$1000$，而且不包含空格。

我们保证$i$和$j$的大小均严格小于$f(n)$的长度，且$|i-j|\leq 1000$;

# Standard Output

对每组测试数据，输出所要求的一段子串。更多信息请参考样例。

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
Hello World 0 1 3
Tanaka Yubiseiharukana 1 0 3
aaa bbb 2 1 4</td><td>ell
Yubi
aabb</td></tr></table>


# Constraints



# Note



# Source


