# 题目描述


<h3>
【题目描述】
</h3>
<p>
<strong> </strong> 
</p>
<p>
<strong>Gty神(xian)犇(chong)从来不缺妹子……</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>他来到了一棵妹子树下，发现每个妹子有一个美丽度……</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>由于Gty很哲♂学，他只对美丽度大于某个值的妹子感兴趣。</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>他想知道某个子树中美丽度大于k的妹子个数。</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>某个妹子的美丽度可能发生变化……</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>树上可能会出现一只新的妹子……</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>维护一棵初始有n个节点的有根树(根节点为1)，树上节点编号为1-n，每个点有一个权值wi。</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>支持以下操作：</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>0 u x          询问以u为根的子树中，严格大于x的值的个数。(u^=lastans,x^=lastans)</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>1 u x          把u节点的权值改成x。(u^=lastans,x^=lastans)</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>2 u x          添加一个编号为&#34;当前树中节点数+1&#34;的节点，其父节点为u，其权值为x。(u^=lastans,x^=lastans)</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>最开始时lastans=0。</strong> 
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入第一行包括一个正整数n(1&lt;=n&lt;=30000)，代表树上的初始节点数。
</p>
<p>
<br/>
</p>
<p>
接下来n-1行，每行2个整数u,v，为树上的一条无向边。
</p>
<p>
<br/>
</p>
<p>
任何时刻，树上的任何权值大于等于0，且两两不同。
</p>
<p>
<br/>
</p>
<p>
接下来1行，包括n个整数wi，表示初始时每个节点的权值。
</p>
<p>
<br/>
</p>
<p>
接下来1行，包括1个整数m(1&lt;=m&lt;=30000)，表示操作总数。
</p>
<p>
<br/>
</p>
<p>
接下来m行，每行包括三个整数 op,u,x：
</p>
<p>
<br/>
</p>
<p>
op,u,x的含义见题目描述。
</p>
<p>
<br/>
</p>
<p>
保证题目涉及的所有数在int内。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
对每个op=0，输出一行，包括一个整数，意义见题目描述。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
2
</p>

<p>
1 2
</p>

<p>
10 20
</p>

<p>
1
</p>

<p>
0 1 5
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>2</pre>
<h3>
【提示】
</h3>
<p>
HZOI2015
</p>
<h3>
【来源】
</h3>
<p>
By AutSky_JadeK  （数据提供：stone ID:3327）
</p>