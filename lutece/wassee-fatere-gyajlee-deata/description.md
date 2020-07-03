
# Content

![无标题.png](/source/lutece/wassee-fatere-gyajlee-deata/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMTMvTFdDQTFEcVJIaDNPaXBtLnBuZw==.png)
——*[志方あきこ - EXEC_over.METHOD_SUBLIMATION/.~omness chs ciel sos infel](https://music.163.com/#/song?id=643155)*

---

有一个圆环形的魔法阵，阵上平均分布着 $2n$ 个点。同时，这个阵上一共有 $n$ 种图形，每一种图形都在恰好两个点上，并且这两个点要么距离小于等于 $2$，要么距离为 $n$（即过这两个点的线段的中点在魔法阵圆心）。并且这个魔法阵还满足：如果 $x,y$ 的图形相同，那么与其相对的两个点图形也相同（即与 $x$ 距离为 $n$ 的点和与 $y$ 距离为 $n$ 的点图形相同）。

定义一个魔法阵的威力值为：将所有图形相同且距离为 $n$ 的点对从魔法阵中删除之后，这个魔法阵会被分成若干段，那么威力值就是这些段段长（即这一段上点的数目）的乘积。如果没有距离为 $n$ 的点对图形相同，那么威力值为 $0$。同时，切下来的这些段中可能存在长度为 $0$ 的段。

现在这位魔法师想知道：对于所有阵上有 $2n$ 个点的魔法阵，威力值之和为多少？两个魔法阵不相同，当且仅当存在点对 $(x,y)$ 在其中一个魔法阵中 $x,y$ 图形相同但在另一个魔法阵中不相同。答案对 $998244353$ 取模。

# Standard Input

一行一个正整数 $n$.

# Standard Output

一行一个整数，表示答案对 $998244353$ 取模后的值。

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
<tr><td>3</td><td>24</td></tr><tr><td>4</td><td>4</td></tr><tr><td>16</td><td>8348748</td></tr></table>


# Constraints

$3\le n \le 5\times 10^4$

# Note

对第一个样例解释：

![无标题.png](/source/lutece/wassee-fatere-gyajlee-deata/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMTcvT0tUdmZiODVSaW5Ba1pNLnBuZw==.png)

上面这 $6$ 种魔法阵中，每一种魔法阵的威力值都为 $2\times 2 = 4$，故威力值之和为 $24$。

# Source


