# 题目描述


<p align="center" style="text-align:center;text-indent:21.0pt;">
	<b>活动选择<span></span></b> 
</p>
<h2>
	【问题描述】
</h2>
<p style="text-indent:21.0pt;">
	假设有一个需要使用某一资源的<span>n</span>个活动组成的集合<span>S</span>，<span>S={1</span>，<span>2</span>，……，<span>n}</span>。该资源一次只能被一个活动所占用，每一个活动有一个<span></span>开始时间<span>Bi</span>和结束时间<span>Ei</span>（<span>Bi&lt;=Ei</span>）。若<span>Bi&gt;Ej</span>或者<span>Bj&gt;Ei</span>，则称活动<span>i</span>和活动<span>j</span>兼容。<span></span> 
</p>
<p style="text-indent:21.0pt;">
	你的任务是：选择由互相兼容的活动组成的最大集合。<span></span> 
</p>
<h2>
	【输入】
</h2>
<p style="text-indent:21.0pt;">
	输入文件共有<span>n+1</span>行，其中第一行包括一个整数<span>n</span>（<span>2&lt;=n&lt;=1000</span>），<span>n</span>表示活动的总数；接下来的<span>n</span>行对应了这<span>n</span>个活动的开始时间和结束时间（中间用空格隔开）。格式为：<span></span> 
</p>
<p>
	    n
</p>
<p>
	    B1 E1
</p>
<p>
	    B2 E2
</p>
<p>
	    ……<span></span> 
</p>
<p>
	    Bn En
</p>
<h2>
	【输出】
</h2>
<p style="text-indent:21.0pt;">
	输出共1行，为最多的活动数。
</p>
<h2>
	【样例】
</h2>
<p style="text-indent:21.0pt;">
	active.in                         
</p>
<pre>11                                  
3 5                                
1 4
12 14
8 12
0 6
8 11
6 10
5 7
3 8
5 9
2 13
</pre>
<p style="text-indent:21.0pt;">
	active.out
</p>
<pre>4</pre>
<h3>
	【样例说明】
</h3>
<p>
	被选中的活动可以是2.3.6.8号活动，总共有4项。
</p>
