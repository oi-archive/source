
# Description

<div class="content"><div>背景</div>
<div>有一天，小Q梦见自己来到了理想国的幻想之乡。</div>
<div>描述</div>
<div>有一天，小Q梦见自己来到了理想国的幻想之乡。幻想乡有无穷户居民，第i个家庭住在编号为i的房屋里，编号从1开始，到正无穷。</div>
<div>居民们的房屋之间有着许多种道路，其中第k种道路只连接在编号为k的倍数且在k的倍数中连续的房屋之间。例如第1种道路连接在编号为(1,2),(2,3),(3,4)…的房屋之间，而第3种道路只连接在编号为(3,6),(6,9),(9,12)…的房屋之间。</div>
<div>小Q要抓紧睡梦的时间来拜访幻想之乡中的贵人，他希望你能帮他完成这场幻想之旅。他经常会从某个编号为i的房屋只走某种道路快速到达某个编号为j的房屋，比如说从编号为4的房屋走到编号为8的房屋，可以走4-&gt;5-&gt;6-&gt;7-&gt;8，也可以走4-&gt;6-&gt;8，甚至可以走4-&gt;8一步到达目的地。</div>
<div>他很好奇，如果他的起点房屋的编号是不大于n的，终点房屋的编号是不大于m的，对于所有可能的起点与终点，他最少会走多少条路，注意他的移动只会选择一种道路。</div>
<div>为了避免精度误差，他希望你能告诉他所有可能的起点与终点所对应的经过的最少边数之和。</div>
<div>由于这个数可能超过10^18，但是不会很大，所以你只需要求出它对两个质数10^9+7和10^9+9的模值即可，小Q的数学很好，他会算出原来的答案</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数T，表示小Q有T组好奇的问题。</div>
<div>接下来是T组问题，每组问题占一行，共两个正整数n, m，空格隔开。</div>
<p></p></div>

# Output

<div class="content"><p>共T行，每行两个空格隔开的整数，表示每组问题分别模10^9+7和10^9+9的答案。</p>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
3 3 <br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 8 <br/>
9 9</span></div>

# Hint

<div class="content"><p></p><p>100%的数据 T &lt;= 1000, n, m &lt;= 2*10^6</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

