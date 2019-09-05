# 题目描述


<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【问题描述】</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">现在要把m本有顺序的书分给k个人复制（抄写），每一个人的抄写速度都一样，一本书不允许给两个（或以上）的人抄写，分给每一个人的书，必须是连续的，比如不能把第一、第三、第四本书给同一个人抄写。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">现在请你设计一种方案，使得复制时间最短。</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;color:#000000;"><span style="color:#000000;">复制时间为抄写页数最多的人用去的时间。</span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入】</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行两个整数m，k；（k≤m≤500）</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二行m个整数，第i个整数表示第i本书的页数。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出】</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">共k行，每行两个整数，第i行表示第i个人抄写的书的起始编号和终止编号。k行的起始编号应该从小到大排列，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>如果有多解，输出任意一个可行解。</span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例】</span> 
</p>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">books.in</span><br/>
<span style="font-weight:bold;font-size:16px;font-family:&#39;Microsoft YaHei&#39;;"></span><span style="font-weight:bold;font-size:10.5pt;font-family:宋体;"></span> 
</p>
<pre>9 3                              
1 2 3 4 5 6 7 8 9      
</pre>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">books.out</span> 
</p>
<pre>1 5
6 7
8 9</pre>
<p>
<br/>
</p>
