
# Description

<div class="content"><p><span style="font-size: medium">给出一个N个顶点、M条边的无向图，边(u,v)有权值w(u,v)，顶点i也有权值p(i)，<br/>
并且对于每条边(u,v)都满足p(u)+p(v)&gt;=w(u,v)。<br/>
现在要将顶点i的权值减去z(i)，其中0&lt;=z(i)&lt;=p(i)。<br/>
修改后设顶点i的权值p&#39;(i)=p(i)-z(i)，对于每条边(u,v)都满足p&#39;(u)+p&#39;(v)=w(u,v)。<br/>
求sum{z(i)}的最小值和最大值。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行两个正整数n,m (n&lt;=500,000, m&lt;=3,000,000)。<br/>
第二行n个整数，依次表示p(1),p(2),...,p(n) (0&lt;=p(i)&lt;=10^6)。<br/>
下面m行，每行三个整数u,v,w (1&lt;=u,v&lt;=n, 0&lt;=w&lt;=10^6)，表示存在一条权值为w的边(u,v)。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
两个正整数，分别表示sum{z(i)}的最小值和最大值，如果不存在方案就输出NIE。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">For the input data:<br/>
3 2<br/>
5 10 5<br/>
1 2 5<br/>
2 3 3<br/>
the correct result is:<br/>
12 15<br/>
whereas for the following input data: <br/>
3 3<br/>
1 1 1<br/>
1 2 1<br/>
1 3 1<br/>
3 2 1<br/>
the correct result is: <br/>
NIE</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Oimaster">鸣谢Oimaster</a></p></div>

