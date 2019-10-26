
# Description

<div class="content">给一张地图，地图上有一些城市，城市之间可能有线路连通，我们用一个无向图来表示以简化概念，每条边有个权值，表示选择这条边需要花费的费用。给定4对顶点(可能重复)，求一个权值最小的边集，使得任意一对顶点可以由选出的边集中的边相连。
按照惯例，下面给出一个例子：
<img border="0" src="/source/bzoj/1402/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0MDIuanBn.jpg"/>
</div>

# Input

<div class="content">第1行2个整数，n和m，分别表示城市的个数和边的个数。
接下来n行，每行一个字符串，表示每个城市的名字。城市的名字为一个不超过20个字符，由小写字母构成的字符串。
再接下来m行，每行给出s1,s2和w，其中s1,s2为城市的名字，w为他们之间边的权值。
最后，给出4行，每行给出两个字符串，分别为要求的一对城市的名字。
</div>

# Output

<div class="content">一行，输出最小的花费。

</div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1：<br/>
10 15<br/>
stockholm<br/>
amsterdam<br/>
london<br/>
berlin<br/>
copenhagen<br/>
oslo<br/>
helsinki<br/>
dublin<br/>
reykjavik<br/>
brussels<br/>
oslo stockholm 415<br/>
stockholm helsinki 396<br/>
oslo london 1153<br/>
oslo copenhagen 485<br/>
stockholm copenhagen 522<br/>
copenhagen berlin 354<br/>
copenhagen amsterdam 622<br/>
helsinki berlin 1107<br/>
london amsterdam 356<br/>
berlin amsterdam 575<br/>
london dublin 463<br/>
reykjavik dublin 1498<br/>
reykjavik oslo 1748<br/>
london brussels 318<br/>
brussels amsterdam 173<br/>
stockholm amsterdam<br/>
oslo london<br/>
reykjavik dublin<br/>
brussels helsinki<br/>
<br/>
样例输入2：<br/>
2 1<br/>
first<br/>
second<br/>
first second 10<br/>
first first<br/>
first first<br/>
second first<br/>
first first<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1：<br/>
3907<br/>
<br/>
样例输出2：<br/>
10<br/>
<br/>
数据范围：<br/>
n&lt;=30,m&lt;=1000,w&lt;=10000。<br/>
<br/>
<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

