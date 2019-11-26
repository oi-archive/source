# 

 
 # 题目背景 
<p><span style="line-height: 20.8px;">西伯利亚北部的寒地，坐落着由&nbsp;N&nbsp;个小岛组成的岛屿群，我们把这些小岛依次编号为&nbsp;1&nbsp;到&nbsp;N&nbsp;。&nbsp;</span></p> 

 
 # 题目描述 
<p>起初，岛屿之间没有任何的航线。后来随着交通的发展，逐渐出现了一些连通两座小岛的航线。例如增加一条在&nbsp;u&nbsp;号小岛与&nbsp;v&nbsp;号小岛之间的航线，这条航线的用时为&nbsp;e。&nbsp;那么沿着这条航线，u&nbsp;号小岛上的人可以前往&nbsp;v&nbsp;号小岛，同样的&nbsp;v&nbsp;号小岛上的人也可以前往&nbsp;u&nbsp;号小岛，其中沿着这一条航线花费的时间为&nbsp;e。</p>

<p>同时，随着旅游业的发展，越来越多的人前来游玩。那么两个小岛之间的最短路径是多少便成为了饱受关注的话题。</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>输入共&nbsp;M+1&nbsp;行。</p>

<p>第一行有两个整数&nbsp;N&nbsp;和&nbsp;M，分别表示小岛的数与总操作数。</p>

<p>接下来的&nbsp;M&nbsp;行，每行表示一个操作，格式如下：</p>

<p>0&nbsp;s&nbsp;t：表示询问从&nbsp;s&nbsp;号小岛到&nbsp;t&nbsp;号小岛的最短用时（1&lt;=s&lt;=n,&nbsp;1&lt;=t&lt;=n）。</p>

<p>1&nbsp;u&nbsp;v&nbsp;e：表示新增了一条从&nbsp;u&nbsp;号小岛到&nbsp;v&nbsp;号小岛，用时为&nbsp;e&nbsp;的双向航线（1&lt;=u&lt;=n,&nbsp;1&lt;=v&lt;=n,&nbsp;u&nbsp;&ne;&nbsp;v,&nbsp;1&lt;=e&lt;=10^6）。</p> 

 
 # 输出格式 
<p>输出针对每一次询问，单独输出一行。</p>

<p>对于每一组询问来说，如果不存在可行的道路，则输出&nbsp;-1，否则输出最短用时。</p> 

 
 # 提示 
<div class="am-g">
<div class="am-u-md-6"><strong>输入样例#1：</strong>
<pre>
3&nbsp;8&nbsp;
1&nbsp;3&nbsp;1&nbsp;10&nbsp;
0&nbsp;2&nbsp;3&nbsp;
1&nbsp;2&nbsp;3&nbsp;20&nbsp;
1&nbsp;1&nbsp;2&nbsp;5&nbsp;
0&nbsp;3&nbsp;2&nbsp;
1&nbsp;1&nbsp;3&nbsp;7&nbsp;
1&nbsp;2&nbsp;1&nbsp;9&nbsp;
0&nbsp;2&nbsp;3</pre>
</div>

<div class="am-u-md-6"><strong>输出样例#1：</strong>

<pre>
-1
15
12</pre>
</div>
</div>

<div class="am-g">
<div class="am-u-md-6"><strong>输入样例#2：</strong>

<pre>
5&nbsp;16
1&nbsp;1&nbsp;2&nbsp;343750
1&nbsp;1&nbsp;3&nbsp;3343
1&nbsp;1&nbsp;4&nbsp;347392
1&nbsp;1&nbsp;5&nbsp;5497
1&nbsp;2&nbsp;3&nbsp;123394
1&nbsp;2&nbsp;4&nbsp;545492
1&nbsp;2&nbsp;5&nbsp;458
1&nbsp;3&nbsp;4&nbsp;343983
1&nbsp;3&nbsp;5&nbsp;843468
1&nbsp;4&nbsp;5&nbsp;15934
0&nbsp;2&nbsp;1
0&nbsp;4&nbsp;1
0&nbsp;3&nbsp;2
0&nbsp;4&nbsp;2
0&nbsp;4&nbsp;3
0&nbsp;5&nbsp;3</pre>
</div>

<div class="am-u-md-6"><strong>输出样例#2：</strong>

<pre>
5955
21431
9298
16392
24774
8840</pre>

<p>对于100%的数据，N&lt;=1000且M&lt;=5000。</p>
</div>
</div> 
