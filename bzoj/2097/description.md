
# Description

<div class="content">
Farmer John为了保持奶牛们的健康，让可怜的奶牛们不停在牧场之间
的小路上奔跑。这些奶牛的路径集合可以被表示成一个点集和一些连接
两个顶点的双向路，使得每对点之间恰好有一条简单路径。简单的说来，
这些点的布局就是一棵树，且每条边等长，都为1。

对于给定的一个奶牛路径集合，精明的奶牛们会计算出任意点对路径的最大值，
我们称之为这个路径集合的直径。如果直径太大，奶牛们就会拒绝锻炼。

Farmer John把每个点标记为1..V (2 &lt;= V &lt;= 100,000)。为了获得更加短
的直径，他可以选择封锁一些已经存在的道路，这样就可以得到更多的路径集合，
从而减小一些路径集合的直径。

我们从一棵树开始，FJ可以选择封锁S (1 &lt;= S &lt;= V-1)条双向路，从而获得
S+1个路径集合。你要做的是计算出最佳的封锁方案，使得他得到的所有路径集合
直径的最大值尽可能小。

Farmer John告诉你所有V-1条双向道路，每条表述为：顶点A_i (1 &lt;= A_i &lt;= V) 
和 B_i (1 &lt;= B_i &lt;= V; A_i!= B_i)连接。

我们来看看如下的例子：线性的路径集合(7个顶点的树)

                   1---2---3---4---5---6---7

如果FJ可以封锁两条道路，他可能的选择如下：

		   1---2 | 3---4 | 5---6---7

这样最长的直径是2，即是最优答案(当然不是唯一的)。
</div>

# Input

<div class="content">* 第1行： 两个空格分隔的整数V和S

* 第2...V行： 两个空格分隔的整数A_i和B_i

</div>

# Output

<div class="content">
* 第1行：一个整数，表示FJ可以获得的最大的直径。
</div>

# Sample Input

<div class="content"><span class="sampledata">7 2<br/>
6 7<br/>
3 4<br/>
6 5<br/>
1 2<br/>
3 2<br/>
4 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

