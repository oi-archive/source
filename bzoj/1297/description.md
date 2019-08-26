
# Description

<div class="content"><p>windy在有向图中迷路了。 该有向图有 N 个节点，windy从节点 0 出发，他必须恰好在 T 时刻到达节点 N-1。 现在给出该有向图，你能告诉windy总共有多少种不同的路径吗？ 注意：windy不能在某个节点逗留，且通过某有向边的时间严格为给定的时间。</p></div>

# Input

<div class="content"><p>第一行包含两个整数，N T。 接下来有 N 行，每行一个长度为 N 的字符串。 第i行第j列为&#39;0&#39;表示从节点i到节点j没有边。 为&#39;1&#39;到&#39;9&#39;表示从节点i到节点j需要耗费的时间。</p></div>

# Output

<div class="content"><p>包含一个整数，可能的路径数，这个数可能很大，只需输出这个数除以2009的余数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例一】<br/>
2 2<br/>
11<br/>
00<br/>
<br/>
【输入样例二】<br/>
5 30<br/>
12045<br/>
07105<br/>
47805<br/>
12024<br/>
12345<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例一】<br/>
1<br/>
<br/>
【样例解释一】<br/>
0-&gt;0-&gt;1<br/>
<br/>
【输出样例二】<br/>
852<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>30%的数据，满足 2 &lt;= N &lt;= 5 ； 1 &lt;= T &lt;= 30 。 100%的数据，满足 2 &lt;= N &lt;= 10 ； 1 &lt;= T &lt;= 1000000000 。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

