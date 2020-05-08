
# Content

Kanade ~~为了凑够学分毕业，被迫~~选了机器学习技术与应用这门课。但她一加课程群就感觉很不对。

「这个群里是就我不会机器学习了吗？」

课上老师讲到了聚类算法。聚类算法是无监督学习中的一种十分重要的算法。这类算法需要找到一个数据集的划分，使得每个数据集内部对象间相似度最大化，数据集之间相似度最小化。

（诶？说到这儿你就会做了吗？这个群里是就我不会机器学习了吗？）

课程实验是实现 DBSCAN 算法。DBSCAN 算法是一个比较有代表性的基于密度的聚类算法。但是 Kanade 不会管这些，因为实验占分少（实际上实验占 40% 平时 10%，她上课时没认真听就听反了，于是她没了）。

甚至没怎么听过课的 Kanade 决定瞎写并且随便水水实验报告就过去了（因为她要去学计网）。 Kanade 的数据集样本空间为 $\mathbb{R}^2$，即，样本可以看做二维 Cartesian 坐标系下的一点 $(x_i,y_i)$。定义两点之间的距离为两点之间的 Euclidean 距离，即，令 $P,Q$ 为平面上两点，则两点之间距离 $d(P,Q)=\sqrt{(x_P-x_Q)^2+(y_P-y_Q)^2}$。

令 $S,T$ 为两不同样本，$D$ 为数据集全集，若 $\forall i\in D,i\neq T,i\neq S,\text{s.t.}\ d(S,T)\le d(S,i)$，则认为点 $S$ 与 $T$ 类别相同。若有多个距离最小的点，取这些点中横坐标最大的那个点为 $T$，若还有多个，则取纵坐标最大的那个点为 $T$。若 $A,B$ 同类，$B.C$ 同类，则认为 $A,C$ 同类，若 $A,B$ 同类，则认为 $B,A$ 也是同类的，认为 $A$ 与它本身是同类的。

现在样本数据集大小为 $n$，Kanade 要处理 $m$ 个查询，每个查询都是查询两个点是否属于同一类。

# Standard Input

第一行两个整数 $n,m$，分别表示数据集大小和问题个数。

接下来 $n$ 行，每行两个整数 $x_i,y_i$，表示第 $i$ 个样本点 $(x_i,y_i)$。

接下来 $m$ 行，每行两个整数 $a,b$，表示询问 $a,b$ 是否为同一类的点。

# Standard Output

输出 $m$ 行，第 $i$ 行表示对第 $i$ 个查询的回答，如果是同一类则输出 `Kanade`，否则输出 `Yuzuru`。

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
0 0
0 1
-1000000000 0
-1000000000 1
1 2
1 3
1 4
2 3
2 4
3 4</td><td>Kanade
Yuzuru
Yuzuru
Yuzuru
Yuzuru
Kanade</td></tr></table>


# Constraints

$1\le n,m\le 2\times 10^5,|x_i|,|y_i|\le 10^9,1\le a,b\le n$，保证没有任意两点重合。

保证所有样本点在二维平面或平面上有限条直线上**均匀随机**。

# Note



# Source


