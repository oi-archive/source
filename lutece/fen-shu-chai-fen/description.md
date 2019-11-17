
# Content

任何一个分数都能才成若干个单位分数(形如1/a的, a是自然数)的和。

对于一个分数$\frac{a}{b}$,表示方法有很多种，但是哪种最好呢？ 

首先，加数少的比加数多的好，其次，加数个数相同的，最小的分数越大越好，如果还是相同，那么第二小的分数越大越好，依次类推下去。

例如对于$\frac{19}{45}$，下列方法都是合法的： 

$\frac{19}{45}=\frac{1}{3} + \frac{1}{12} + \frac{1}{180}$ 

$\frac{19}{45}=\frac{1}{3} + \frac{1}{15} + \frac{1}{45}$

$\frac{19}{45}=\frac{1}{3} + \frac{1}{18} + \frac{1}{30}$

$\frac{19}{45}=\frac{1}{4} + \frac{1}{6} + \frac{1}{180}$

$\frac{19}{45}=\frac{1}{5} + \frac{1}{6} + \frac{1}{18}$

但是最好的是最后一种，因为$\frac{1}{18}$比$\frac{1}{180}$, $\frac{1}{45}$, $\frac{1}{30}$, $\frac{1}{180}$都大。 

现在给出$a,b$($0<a<b<1000$),求最好的表达方式。

# Standard Input

第一行有一个整数$T$，表示有$T$($T\leq 50$)组测试数据，每组测试数据为一行包含$a,b$($0<a<b<1000$)。

# Standard Output

每组测试数据若干个数，自小到大排列，依次是单位分数的分母。

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
<tr><td>1
19 45</td><td>5 6 18</td></tr></table>


# Constraints



# Note



# Source


