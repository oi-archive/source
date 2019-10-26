
# Content

`SSRaligun` 有$n$个妹子(为了方便记忆，邱老师给每一个妹子独一无二的标号$id，1 \leq id \leq n)$，他一直致力于让他的妹子们和谐相处，有一天`SSRaligun`觉得是时候检测一下他的妹子们的团结度了。`SSRaligun`咨询了每一个妹子，她跟其他妹子中的哪几个可以和谐相处。但`SSRaligun`又是如此的忙碌，因为他要帮集训队的其他人去购置北京烤鸭，请你来帮他计算一下他的妹子们的总团结度。

机智的`SSRaligun`给出了总团结度的计算方法：

他首先将他的n个妹纸化作了一张图中的$n$个结点，如果某两个妹子可以和谐相处，那么就在这两个结点之间连上一条边。

设取出$L$个点中存在$i$条边的不同取法有$x\_i$种（某一条边存在的条件是这条边的两个端点都在所选择的$L$个点中）团结度$P=x\_1+2 \times x\_2 + 3 \times x\_3 + 4 \times x\_4 + \cdots + [\frac{（L-1）\times L}{2}] \times x\_{[\frac{（L-1）\times L}{2}]}$

# Standard Input

输入包含多组数据。第一行是一个整数T表示数据组数$（0 < T \leq 20）$。

接下来每组数据的第一行，即三个整数$n,m,L$分别是`SSRaligun`的妹子个数，他妹子之间互相和谐的对数，定义团结度时随手召唤的妹子个数$（3 \leq n \leq 100,0 \leq m \leq min(\frac{n \times (n-1)}{2},1000),3 \leq L \leq min(9,n)）$。

接下来就是$m$行：

每一行有两个数$a,b（1 \leq a,b \leq n,并且a!=b）$，表示妹子$a$和妹子$b$能够和谐相处。（没有两行的$a,b$完全相同）

# Standard Output

每组数据，输出一个整数$P$，表示`SSRaligun`的妹子的团结度。

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
<tr><td>2
5 2 4 
1 2
1 3
4 3 3
1 2
1 3
1 4
</td><td>6
6</td></tr></table>


# Constraints



# Note

![title](/source/lutece/ssraligun-and-his-girl-friends/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTAyMC8yMDE0MTIxMzAwMDY0MDk4NjkuanBn.jpg)

样例$1$表示的妹子们的关系图如上图：

在所有的选择中：

选择 $[1,3,4,5]，[1,2,4,5]$ 存在一条边，所以$x\_1=2$；
选择 $[1,2,3,5]$,选择$[1,2,3,4]$存在两条边，所以$x\_2=2$，
$x\_3,x\_4 \cdots x\_[ \frac{(L-1）\times L}{2}]$都为$0$，所以团结度$P=1\times x\_1+2 \times x\_2=6$.

# Source


