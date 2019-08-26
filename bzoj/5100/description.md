
# Description

<div class="content"><div>有一棵n个点的无根树，每条边有一个正整数权值，表示长度，定义两点距离为在树上的最短路径的长度。</div>
<div>已知2到n-1每个点在树上与1和n的距离，请根据这些信息还原出这棵树。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数n(2&lt;=n&lt;=500000)，表示点数。</div>
<div>第二行包含n-2个正整数d(1,2),d(1,3),...,d(1,n-1)，分别表示每个点到1的距离。</div>
<div>第三行包含n-2个正整数d(n,2),d(n,3),...,d(n,n-1)，分别表示每个点到n的距离。</div>
<div>输入数据保证1&lt;=d&lt;=1000000。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>若无解，输出NIE。</div>
<div>否则第一行输出TAK，接下来n-1行每行三个正整数u,v,c(1&lt;=u,v&lt;=n,1&lt;=c&lt;=1000000)</div>
<div>表示存在一条长度为c的连接u和v两点的树边。</div>
<div>若有多组解，输出任意一组。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
6 6 2 2 1<br/>
5 3 5 1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
1 5 2<br/>
5 7 1<br/>
5 2 4<br/>
7 3 3<br/>
1 4 2<br/>
1 6 1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传试题">鸣谢Claris上传试题</a></p></div>

