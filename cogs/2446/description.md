# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span lang="en-us"> </span> 
</p>
<p>
<img src="/upload/image/20170220/20170220062127_82634.png" alt=""/> 
</p>
<p>
水母与树有着密切的联系，水母的很多性质可以由树拓展而得，水母的很多问题可以由断链后的树解决。
</p>
<p>
   某天，小TLE正在研究水母，突然他有了一个疑问：水母的深度是什么？
</p>
<p>
   这个问题对小TLE来说太难了！！因为他并不能确定谁是水母的根！！
</p>
<p>
   于是小TLE找到了CE学长，CE学长：你先去解决这道与深度有关的问题，我再教你这道题！
</p>
<p>
CE学长的问题是这样的：
</p>
<p>
     已知一个有n个结点的树的dfs序和bfs序，求其可能的深度的范围。
</p>
<p>
<br/>
</p>
<p>
小TLE当然不会这个问题了，于是他又找到了你：小RE！
</p>
<h3>
【输入格式】
</h3>
<p>
<span lang="en-us"> </span> 
</p>
<p>
第一行一个整数n
</p>
<p>
接下来一行n个整数表示dfs[i]
</p>
<p>
接下来一行n个整数表示bfs[i]
</p>
<h3>
【输出格式】
</h3>
<div class="ptx" lang="zh-CN">
<span lang="en-us"> 
<p>
输出两个整数mn,mx表示这棵树的深度范围[mn,mx]
</p>
</span> 
</div>
<h3>
【样例输入】
</h3>
<pre class="sio"><p>
5
</p>

<p>
1 2 4 5 3
</p>

<p>
1 2 3 4 5
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre class="sio"><p>
3 4
</p>
</pre>
<h3>
【提示】
</h3>
<p>
  样例解释：<img src="/upload/image/20170529/20170529200601_44158.png" alt=""/> 
</p>
<p>
数据范围：
</p>
<p>
对于20%的数据n&lt;=10
</p>
<p>
对于40%的数据n&lt;=100
</p>
<p>
对于60%的数据n&lt;=2000
</p>
<p>
对于80%的数据n&lt;=1000,000
</p>
<p>
对于100%的数据n&lt;=10,000,000
</p>
<p>
数据保证存在一棵合法的树同时满足dfs序和bfs序。
</p>
<p>
对于树中任意的三个节点a,b,fa,如果a,b都是fa的儿子，则a,b在bfs序中和dfs序中的相对前后位置是一致的。
</p>
<p>
您可能需要[快读代码]:
</p>
<pre class="prettyprint lang-cpp">int read()
{	
	char ch=getchar();
	while(ch&lt;&#39;0&#39;||ch&gt;&#39;9&#39;)ch=getchar();
	int x=0; 
	while(ch&gt;=&#39;0&#39;&amp;&amp;ch&lt;=&#39;9&#39;)x=x*10+ch-48,ch=getchar(); 
	return x;
}</pre>
<p>
您可能需要[开栈代码]：
</p>
<pre class="prettyprint lang-cpp">        int __size__=32&lt;&lt;20;
	char *__p__=(char*)malloc(__size__)+__size__;
	__asm__(&#34;movl %0, %%esp\n&#34;::&#34;r&#34;(__p__));</pre>
<h3>
【来源】
</h3>
<p>
一只名字很长的蒟蒻。
</p>
