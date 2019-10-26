
# Content

尊贵的`oydy`在完成了他的征途后，想要去往外星球X进行私访(~~以便以后可以征服这颗星球~~)。  
来到星球X后，他的小弟`FoolishMe`发现这颗星球有n个城市和m条道路，每条道路双向连接了两个城市$(u,v)$。但由于星球X比较贫穷，虽然任意两个城市都可以互相到达，但是道路数非常少$(m \leq n + 30)$。现在`oydy`想要从1号城市出发，按照一定的顺序访问星球X上的若干个城市，并且使得走的总路程最少。规划路线的工作当然是交给他的小弟`FoolishMe`来做了，但是他并不知道自己所规划的路线是否是最短的，所以他希望你能够计算出最短路程是多少以便他用来检验自己所规划的路线是否是最短的。

# Standard Input

第一行两个数字$n$和$m$表示星球X有n个城市和m条双向道路。$(2 \leq n \leq 10^5,n - 1 \leq m \leq n + 30)$  
接下来$m$行，每行3个数字$u,v,w$表示连接$u$城市到$v$城市的双向道路的路径长度为$m$ $(1 \leq u,v \leq n, 1 \leq w \leq 10^5)$
接下来一行读入一个数字$T$，表示从1号城市出发后想要按顺序访问的城市个数。$(1 \leq T \leq 10^5)$  
接下来一行是一个长度为$T$的序列$S$，表示oydy想要按顺序访问的城市序列。第$i$个数$S[i]$表示想要访问的第$i$个城市。$(1 \leq S[i] \leq n)$

# Standard Output

输出一个数字，表示从1号城市出发，按顺序访问完序列$S$所需要的最短路径。

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
<tr><td>4 4  
1 2 2  
2 4 1  
2 3 1  
3 4 1  
2  
4 2  </td><td>4</td></tr></table>


# Constraints



# Note

样例解释：  
从1出发，先走1->2->4到达4号城市，路程为3  
再走4->2到达2号城市，路程为1  
总路程为4，并且按顺序访问了4号城市和2号城市。

# Source


