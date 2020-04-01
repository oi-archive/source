
# Description

<div class="content"><p>　　有n个城市和m条单向道路，城市编号为1~n。每条道路连接两个不同的城市，且任意两条道路要么起点不同要<br/>
么终点不同，因此n和m满足m&lt;=n(n-1)。给定两个城市a和b，可以给a到b的所有简单路（所有城市最多经过一次，<br/>
包括起点和终点）排序：先按长度从小到大排序，长度相同时按照字典序从小到大排序。你的任务是求出a到b的第<br/>
k短路。</p></div>

# Input

<div class="content"><p>　　输入第一行包含五个正整数n, m, k, a, b。以下m行每行三个整数u, v, l，表示从城市u到城市v有一条长度<br/>
为l的单向道路。100%的数据满足：2&lt;=n&lt;=50, 1&lt;=k&lt;=200</p></div>

# Output

<div class="content"><p>　　如果a到b的简单路不足k条，输出No，否则输出第k短路：从城市a开始依次输出每个到达的城市，直到城市b，<br/>
中间用减号&#34;-&#34;分割。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
5 20 10 1 5<br/>
1 2 1<br/>
1 3 2<br/>
1 4 1<br/>
1 5 3<br/>
2 1 1<br/>
2 3 1<br/>
2 4 2<br/>
2 5 2<br/>
3 1 1<br/>
3 2 2<br/>
3 4 1<br/>
3 5 1<br/>
4 1 1<br/>
4 2 1<br/>
4 3 1<br/>
4 5 2<br/>
5 1 1<br/>
5 2 1<br/>
5 3 1<br/>
5 4 1<br/>
【样例输入2】<br/>
4 6 1 1 4<br/>
2 4 2<br/>
1 3 2<br/>
1 2 1<br/>
1 4 3<br/>
2 3 1<br/>
3 4 1<br/>
【样例输入3】<br/>
3 3 5 1 3<br/>
1 2 1<br/>
2 3 1<br/>
1 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
1-2-4-3-5<br/>
【样例输出2】<br/>
1-2-3-4<br/>
【样例输出3】<br/>
No</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">第一个例子有5个城市，所有可能出现的道路均存在。从城市1到城市5一共有5条简单路</span></p><br/>
<p><span style="font-size: medium"><img width="447" height="216" alt="" src="/source/bzoj/1073/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC8xKDQpLnBuZw==.png"/><br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

