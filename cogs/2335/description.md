# 题目描述


<h3>
【题目描述】
</h3>
<p>
</p><p>
S 国的动物园是一个N*M  的网格图，左上角的坐标是(1,1)，右下角的坐标是(N,M)。
</p>
<p>
   小象在动物园的左上角，它想回到右下角的家里去睡觉，但是动物园中有一些老鼠，而
</p>
<p>
小象又很害怕老鼠。动物园里的老鼠是彼此互不相同的。小象的害怕值定义为他回家的路径
</p>
<p>
上可以看见的不同的老鼠的数量。若小象当前的位置为(x1,y1)，小象可以看见老鼠，当且仅
</p>
<p>
当老鼠的位置(x2,y2)满足|x1-x2|+|y1-y2|&lt;=1 。由于小象很困了，所以小象只会走一条最近的路回家，即小象只会向下或者向右走。现在你需要帮小象确定一条回家的路线，使得小象的害怕值最小。
</p>
<p></p>
<h3>
【输入格式】
</h3>
<p>
</p><p>
第一行包含两个用空格隔开的整数，N 和M。
</p>
<p>
   接下来一个N*M  的矩阵表示动物园的地图。其中Aij 表示第i 行第j
</p>
<p>
列上老鼠的数量。 若Aij=0 则表示当前位置上没有老鼠(小象的家里也可能存在老鼠)。
</p>
<p>
输出格式
</p>
<p></p>
<h3>
【输出格式】
</h3>
<p>
输出一个整数，表示路线最小的害怕值是多少
</p>
<h3>
【样例输入】
</h3>
<pre><p>
3 9
</p>

<p>
0 0 1 0 0 0 0 0 1
</p>

<p>
1 1 1 1 1 1 0 1 0
</p>

<p>
1 0 0 1 0 0 1 0 0
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>9 </pre>
<h3>
【提示】
</h3>
<p>
</p><p>
对于10%的数据，1&lt;=N,M&lt;=5。
</p>
<p>
对于100%的数据，1&lt;=N,M&lt;=1000，0&lt;=Aij&lt;=100。
</p>
<p></p>
<h3>
【来源】
</h3>
<p>
HZOI 2016
</p>