# 题目描述


<h3>
【题目描述】
</h3>
<p>
Dingilville的居民正设法找到一块地来修建机场。他们已经有了这片地区的地图。地图是一个由单位格组成的矩形网格，每个单位格由一个整数对(x,y)确定，其中x是横坐标（东到西），y是纵坐标（南到北）。地图中标注了每格的海拔。
</p>
<p>
你的任务是找到一个由单位格组成的，面积最大（即包含最多单位格）的矩形地块，使得：
</p>
<p>
·地块中海拔最高和最低的单位格的海拔之差不超过给定的限制C。
</p>
<p>
·地块的宽度（即从西到东的距离）不超过100.
</p>
<p>
你需要输出满足条件地块的最大面积。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有三个整数U,V,C，代表地图的大小和给定限制。
</p>
<p>
接下来的V行，每行有U个整数Hxy，给出了每格的海拔。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个正整数，即最大面积。
</p>
<h3>
【样例输入】
</h3>
<p>
10 15 4
</p>
<p>
41 40 41 38 39 39 40 42 40 40
</p>
<p>
39 40 43 40 36 37 35 39 42 42
</p>
<p>
44 41 39 40 38 40 41 38 35 37
</p>
<p>
38 38 33 39 36 37 32 36 38 40
</p>
<p>
39 40 39 39 39 40 40 41 43 41
</p>
<p>
39 40 41 38 39 38 39 39 39 42
</p>
<p>
36 39 39 39 39 40 39 41 40 41
</p>
<p>
31 37 36 41 41 40 39 41 40 40
</p>
<p>
40 40 40 42 41 40 39 39 39 39
</p>
<p>
42 40 44 40 38 40 39 39 37 41
</p>
<p>
41 41 40 39 39 40 41 40 39 40
</p>
<p>
47 45 49 43 43 41 41 40 39 42
</p>
<p>
42 41 41 39 40 39 42 40 42 42
</p>
<p>
41 44 49 43 46 41 42 41 42 42
</p>
<p>
45 40 42 42 46 42 44 40 42 41
</p>
<h3>
【样例输出】<br/>
</h3>
<p>
35
</p>
<h3>
【提示】
</h3>
<p>
样例如图：
</p>
<p>
<img src="/upload/image/20140626/20140626223728_51667.png" alt=""/> 
</p>
<p>
1&lt;=U&lt;=700,1&lt;=V&lt;=700
</p>
<p>
0&lt;=C&lt;=10
</p>
<p>
-30000&lt;=Hxy&lt;=30000
</p>
<p>
西南角是（1,1），东北角是（U,V）
</p>
<h3>
【来源】
</h3>
<p>
IOI 1999 A Strip of Land
</p>