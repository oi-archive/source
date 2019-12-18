
# Content

![image](/source/lutece/wei-shi-yao-ni-zhe-yao-shou-lian-a/img/aHR0cDovL2hpcGhvdG9zLmJhaWR1LmNvbS9mZWVkL3BpYy9pdGVtLzI2N2Y5ZTJmMDcwODI4MzhmNWQ3Y2I1ZWI1OTlhOTAxNGQwOGYxYTYuanBn.jpg)

冬马和纱有一首长度为$N$节的乐谱，乐谱每一节有$a_i$个音符，冬马和纱在乐谱里隐藏了一些信息，想传达给北原春希，她每次询问四个数字$l_1,l_2,r_1,r_2$，要求北原春希计算$\sum_{x=0}^{\infty}\text{get}(l_1,r_1,x)\text{get}(l_2,r_2,x)$ ，$get(l,r,x)$表示区间$[l,r]$中，数字$x$出现的次数

可是北原春希是大学霸，轻而易举的解析出了冬马和纱在乐谱里隐藏的信息，冬马很是惊讶：为什么你这么熟练啊

你能在规定时间内解决这道问题，向她证明你也很熟练吗？

# Standard Input

第一行，一个数字 $N$，表示序列长度。
第二行，$N$ 个数字，表示 $a_1∼a_N$。
第三行，一个数字 $Q$，表示询问个数。
第 $4∼Q+3$行，每行四个数字 $l1,r1,l2,r2$表示询问。

$1 \le N,Q \le 50000,1 \le a_i \le N,1 \le l_1 \le r_1 \le N, 1 \le l_2 \le r_2 \le N$

# Standard Output

对于每组询问，输出一行一个数字，表示答案。

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
<tr><td>5
1 1 1 1 1
2
1 2 3 4
1 1 4 4</td><td>4
1</td></tr></table>


# Constraints



# Note



# Source


