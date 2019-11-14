# 题目描述


<h3>
<span style="font-family:Microsoft YaHei;font-size:14px;">【题目描述】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:14px;">  在你的帮助下，蔚蓝来到了埃及.在金字塔里，蔚蓝看到了一个问题，传说，能回答出这个问题的人就能受到埃及法老的祝福，可是蔚蓝日夜奋战，还是想不出来，你能帮帮他么？(XXX: 胡扯,教主怎么可能想不出来= _ =||)（WS这人说的=。=）</span><br/>
<span style="font-family:Microsoft YaHei;font-size:14px;">   问题是这样的： </span><br/>
<span style="font-family:Microsoft YaHei;font-size:14px;">   给定一个序列</span><a1,a2,...,an><span style="font-family:Microsoft YaHei;font-size:14px;">.求最长上升子序列(lis)p1</span><p2<...<pw满足a[p1]<a[p2]<...<a[pw]<br>
<span style="font-family:Microsoft YaHei;font-size:14px;">    例如65 158 170 299 300 155 207 389</span><br/>
<span style="font-family:Microsoft YaHei;font-size:14px;">   LIS=&lt;65,158,170,299,300,389&gt;。</span><br/>
<span style="font-family:Microsoft YaHei;font-size:14px;">   但是，现在还有一个附加条件：求出的最长上升子序列必须含有第K项。</span><br/>
<span style="font-family:Microsoft YaHei;font-size:14px;">   比如，在上面的例子中，要求求出的最长上升子序列必须含有第6项，那么最长上升子序列就是：65 155 207 389。</span></p2<...<pw满足a[p1]<a[p2]<...<a[pw]<br>
</a1,a2,...,an>
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:14px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:14px;">第一行是用空格隔开的两个正整数N、K，含义同上所述.</span><br/>
<span style="font-family:Microsoft YaHei;font-size:14px;"> 第二行N个数，即给出的序列.</span> 
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:14px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:14px;">仅有一个数，表示含有第K项的最长上升子序列的长度.</span> 
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:14px;">【样例输入】</span> 
</h3>
<pre>5 3
1 2 3 2 1
</pre>
<h3>
<span style="font-family:Microsoft YaHei;font-size:14px;">【样例输出】</span> 
</h3>
<pre>3</pre>
<h3>
<span style="font-family:Microsoft YaHei;font-size:14px;">【提示】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:14px;">对于60%的数据，N&lt;=10000;</span><br/>
<span style="font-family:Microsoft YaHei;font-size:14px;"> 对于100%的数据，1&lt;=n&lt;=300000 ,1&lt;=k&lt;=n,序列的每一个数为小于2^31-1 的非负整数.</span> 
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:14px;">【来源】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:14px;">Super Pig（蔚蓝） http://vijos.org/Problem_show.asp?id=1369</span> 
</p>
