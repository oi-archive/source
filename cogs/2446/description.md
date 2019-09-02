

# 题目描述



# 输入格式



# i



# i



# 输出格式


<div class="ptx" lang="zh-CN">
<span lang="en-us"> 

# mn,mx


</span> 
</div>

# 样例输入


<pre class="sio">
# 样例输出


<pre class="sio">
# 提示



# 快读代码


<pre class="prettyprint lang-cpp">int read()
{	
	char ch=getchar();
	while(ch&lt;&#39;0&#39;||ch&gt;&#39;9&#39;)ch=getchar();
	int x=0; 
	while(ch&gt;=&#39;0&#39;&amp;&amp;ch&lt;=&#39;9&#39;)x=x*10+ch-48,ch=getchar(); 
	return x;
}</pre>

# 开栈代码


<pre class="prettyprint lang-cpp">        int __size__=32&lt;&lt;20;
	char *__p__=(char*)malloc(__size__)+__size__;
	__asm__(&#34;movl %0, %%esp\n&#34;::&#34;r&#34;(__p__));</pre>

# 来源


<p>
一只名字很长的蒟蒻。
</p>
