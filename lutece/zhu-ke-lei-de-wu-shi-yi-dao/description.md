
# Content

有一个奇怪的城市，初始时只有一个点

之后每次都会在原来基础上复制三遍，同时在新建两个新的结点来连接这四个副本，同时这两个新建点的边和到这四个副本的边在第$i$次操作时长度为$A[i]$

求$N$次操作后$\displaystyle \sum_{i=1}^{n} \sum_{j=i+1}^{n}dis(i,j)$

请注意这里的$n$表示第$N$次操作后的结点总数

$dis(i,j)$表示第$i$个点到第$j$个点的最短距离

![title](/source/lutece/zhu-ke-lei-de-wu-shi-yi-dao/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTUyMi8yMDE2MTIwMTAxMDQzNTEwNjkucG5n.png)

# Standard Input

输入第一行有一个数$N$

接下来$N$个数，分别代表$A[i]$

数据保证：

$1 \leq N \leq 10^6$

$1 \leq A[i] \leq 9$

# Standard Output

对应每组数据，输出一行表示答案.

答案可能较大，只需要$mod$ $10^9+7$后输出

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
1
</td><td>29
</td></tr><tr><td>2
1 1</td><td>1645
</td></tr></table>


# Constraints



# Note

![title](/source/lutece/zhu-ke-lei-de-wu-shi-yi-dao/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTUyMi8yMDE2MTIwMTAxMDYzMjQyMTEwLnBuZw==.png)

$dis(1,2)$+$dis(1,3)$+$dis(1,4)$+$dis(1,5)$+$dis(1,6)$+$dis(2,3)$+$dis(2,4)$+…… = $29$

# Source


