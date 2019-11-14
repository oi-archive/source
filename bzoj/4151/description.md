
# Description

<div class="content"><div>给定一棵有n个节点的树，相邻两点之间的距离为1。</div>
<div>请找到一个点x，使其满足所有m条限制，其中第i条限制为dist(x,a[i])+dist(x,b[i])&lt;=d[i]。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数t(1&lt;=t&lt;=1000)，表示数据组数。</div>
<div>对于每组数据，第一行包含两个正整数n,m(2&lt;=n,m&lt;=300000)，表示点数、限制数。</div>
<div>接下来n-1行，每行两个正整数x,y(1&lt;=x,y&lt;=n)，表示树上的一条边。</div>
<div>接下来m行，每行三个正整数a[i],b[i],d[i](1&lt;=a[i],b[i]&lt;=n,1&lt;=d[i]&lt;=600000)，描述一条限制。</div>
<div>输入数据保证所有n之和不超过300000，所有m之和也不超过300000。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出t行。第i行输出第i组数据的答案，如果无解输出NIE，否则输出TAK，</div>
<div>然后输出x，如有多组解，输出任意一组。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5 3<br/>
1 2<br/>
2 3<br/>
2 4<br/>
3 5<br/>
1 4 2<br/>
5 5 5<br/>
3 2 1<br/>
3 2<br/>
1 2<br/>
2 3<br/>
1 1 2<br/>
3 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK 2<br/>
NIE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

