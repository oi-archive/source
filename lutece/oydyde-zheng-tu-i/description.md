
# Content

尊贵的`oydy`想要踏遍这片土地上的所有城市!于是就开始了他的征途。  
这片土地上有$n$个城市和$m$条路,每条路连接了两个城市$u$,$v$,被连接的两个城市可以在这条路上**往返**,每次经过某条路的时候都要支付一定的过路费,`oydy`觉得这样太麻烦了,于是他每经过一条路就会`直接把这条路买下来`,这样之后他就可以畅通无阻了(甚至其他人经过时还要给`oydy`过路费!)。  
由于`oydy`是尊贵的,所以在他开始他的征途前,可以直接选择一条路并免费获得这条路的所有权。  
`oydy`掐指一算就知道了完成自己的征途至少需要多少花费,又掐脚一算就知道了自己一开始在选择一条路时`有多少种选择方式`可以达到这个最小花费,他决定考考他的小弟`FoolishMe`,即使`FoolishMe`常年给`oydy`端茶送水,智慧也不及其万分之一,所以需要聪明的你来帮他解决这个问题。

# Standard Input

第一行两个数字$n$和$m$表示这片土地上有n个点和m条路 $(2\leq n \leq 10^5, 1 \leq m \leq 2 \times 10^5)$    
接下来$m$行,每行三个数字$u,v,w$,表示$u$到$v$有一条路,买下这条路的花费为$w$ $(1 \leq u, v \leq n, 1 \leq w \leq 10^9)$

# Standard Output

输出一行中包括两个数,第一个数表示最小花费,第二个数表示方案数,两个数中间用空格隔开

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
<tr><td>4 6 
2 1 1 
1 3 3 
1 4 7 
2 3 2 
4 2 3 
4 3 3 </td><td>3 3</td></tr><tr><td>4 4
1 2 5
2 4 1
1 3 2
3 4 4</td><td>3 2</td></tr></table>


# Constraints



# Note

对于样例,最小的花费是3,oydy一开始有3种选择方式可以达成这个最小花费:  

- oydy一开始选择 4-2 这条边, 他的征途为1->2->4->2->3  
- oydy一开始选择 4-3 这条边, 他的征途为1->2->3->4
- oydy一开始选择 1-4 这条边, 他的征途为1->2->3->2->1->4  

注意:是一开始一条路的选择方式,选择同一条路但征途不同也算同一种方案

# Source


