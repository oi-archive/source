
# Content

沙耶定义了一种新函数:
 
$SagMa(n,m)=\left\\{\begin{matrix}
1 & (n=0)\\\\
\sum\_{i\_n=1}^m\cdots\sum\_{i\_2=1}^{i\_3}\sum\_{i\_1=1}^{i\_2}1 &(n\geq 0, m>0)
\end{matrix}\right.$

举例：

$SagMa(1,3)=\sum\_{i\_1=1}^31=3$

$SagMa(2,3)=\sum\_{i\_2=1}^3\sum\_{i\_1=1}^{i\_2}1=\sum\_{i\_1=1}^11+\sum\_{i\_1=1}^21+\sum\_{i\_1=1}^31=6$

$SagMa(3,3)=\sum\_{i\_3=1}^3\sum\_{i\_2=1}^{i\_3}\sum\_{i\_1=1}^{i\_2}1=\sum\_{i\_2=1}^{1}\sum\_{i\_1=1}^{i\_2}1+\sum\_{i\_2=1}^{2}\sum\_{i\_1=1}^{i\_2}1+\sum\_{i\_2=1}^{3}\sum\_{i\_1=1}^{i\_2}1=1+3+6=10$

请求出$SagMa(n,m)$。

# Standard Input

第一行一个整数$T$，表示有$T$($T\leq 110$)组测试数据。

接下来的$T$行，每行两个整数$n$($0\leq n\leq 10$),$m$($0<m\leq 10$)，表示要求的是$SagMa(n,m)$。

# Standard Output

每组数据输出一行，表示$SagMa(n,m)$的值。

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
1 3
2 3
3 3</td><td>3
6
10</td></tr></table>


# Constraints



# Note



# Source


