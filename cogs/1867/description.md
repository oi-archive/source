# 题目描述


<p>
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
</p>
<h3>
<span style="font-family:sans-serif;font-size:20px;font-weight:bold;background-color:aliceblue;">【问题描述】</span> 
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">Ray 乐忠于旅游，这次他来到了T 城。</span>T 城是一个水上城市，一共有 N 个景点，有些景点之间会用一座桥连接。为了方便游客到达每个景点但又为了节约成本，T 城的任意两个景点之间有且只有一条路径。换句话说，T 城中只有N - 1 座桥。Ray 发现，有些桥上可以看到美丽的景色，让人心情愉悦，但有些桥狭窄泥泞，令人烦躁。于是，他给每座桥定义一个愉悦度w，也就是说，Ray 经过这座桥会增加w 的愉悦度，这或许是正的也可能是负的。有时，Ray 看待同一座桥的心情也会发生改变。现在，Ray想让你帮他计算从u 景点到v 景点能获得的总愉悦度。有时，他还想知道某段路上最美丽的桥所提供的最大愉悦度，或是某段路上最糟糕的一座桥提供的最低愉悦度。
</p>
<h3>
【输入格式】
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">输入的第一行包含一个整数N，表示T 城中的景点个数。N &lt;= </span>100000。
</p>
<p>
接下来N - 1 行，每行三个整数u、v 和w，表示有一条u 到v，使 Ray 愉悦度增加w 的桥。桥的编号为1 ... N - 1。|w| &lt;= 1000。
</p>
<p>
输入的第N + 1 行包含一个整数M，表示Ray 的操作数目。M &lt;= 500000。
</p>
<p>
接下来的M 行，操作有如下三种形式：
</p>
<p>
C i w，表示Ray 对于经过第i 座桥的愉悦度变成了w。
</p>
<p>
N u v，表示Ray 对于经过景点u 到v 的路径上的每一座桥的愉悦度都变成原来的相反数。
</p>
<p>
SUM u v，表示询问从景点u 到v 所获得的总愉悦度。
</p>
<p>
MAX u v，表示询问从景点u 到v 的路径上的所有桥中某一座桥所提供的最大愉悦度。
</p>
<p>
MIN u v，表示询问从景点u 到v 的路径上的所有桥中某一座桥所提供的最小愉悦度。
</p>
<p>
测试数据保证，任意时刻，Ray 对于经过每一座桥的愉悦度的绝对值小于等于1000。
</p>
<h3>
【输出格式】
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">对于每一个询问(操作S、MAX 和MIN)，输出答案。</span> 
</p>
<h3>
【样例输入】
</h3>
<pre>3
0 1 1
1 2 2
8
SUM 0 2
MAX 0 2
N 0 1
SUM 0 2
MIN 0 2
C 1 3
SUM 0 2
MAX 0 2
</pre>
<h3>
【样例输出】
</h3>
<pre>3
2
1
-1
5
3
</pre>
<h3>
【来源】
</h3>
<p>
2011中国国家集训队命题答辩（宋方睿）
</p>
