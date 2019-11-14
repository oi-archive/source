# 题目描述


<p>
<span><span style="font-family:宋体;"><b><span style="font-size:24px;">【问题描述】</span></b><span></span></span></span> 
</p>
<p style="text-indent:24pt;">
<span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">检查一个如下的</span></span><span style="font-size:18px;">6 x 6</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">的跳棋棋盘，有六个棋子被放置在棋盘上，使得每行，每列，每条对角线</span></span><span style="font-size:18px;">(</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">包括两条主对角线的所有对角线</span></span><span style="font-size:18px;">)</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">上都至多有一个棋子，如下例，就是一种正确的布局。</span></span></span> 
</p>
<img alt="" src="/upload/image/20130723/20130723154915_96337.jpg"/><br/>
<p style="text-indent:24pt;">
<span style="font-size:small;"><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">上面的布局可以用序列</span></span><span style="font-size:18px;">2 4 6 1 3 5</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">来描述，第</span></span><span style="font-size:18px;">i</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">个数字表示在第</span></span><span style="font-size:18px;">i</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">行的相应位置有一个棋子，如下：</span></span><span style="font-family:;"> <span></span></span></span> 
</p>
<p style="text-indent:24pt;">
<span style="font-size:small;"><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">行号</span></span><span style="font-size:18px;"> 1 2 3 4 5 6</span></span> 
</p>
<p style="text-indent:24pt;">
<span style="font-size:small;"><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">列号</span></span><span style="font-size:18px;"> 2 4 6 1 3 5</span></span> 
</p>
<p style="text-indent:24pt;">
<span style="font-size:small;"><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">这只是跳棋放置的一个解。请写一个程序找出所有跳棋放置的解，并把它们以上面的序列方法输出。解按字典顺序排列，请输出前</span></span><span style="font-size:18px;">3</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">个解，最后一行是解的总个数。</span></span><span style="font-family:;"> </span></span> 
</p>
<p>
<span style="font-size:small;"><span style="font-family:宋体;"><span style="font-size:24px;">【输入格式】</span><span style="font-family:;"></span></span></span> 
</p>
<p style="text-indent:23.65pt;">
<span style="font-size:small;"><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">一个数字</span></span><span style="font-size:18px;">N (6 &lt;= N &lt;= 14) </span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">表示棋盘是</span></span><span style="font-size:18px;">N x N</span><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">大小的。</span></span><span style="font-family:;"> </span></span> 
</p>
<p>
<span style="font-family:宋体;font-size:24px;">【输出格式】</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-size:small;"><span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">前三行为前三个解，每个解的两个数字之间用一个空格隔开。第四行只有一个数字，表示解的总数。</span></span><span style="font-family:;"> <span></span></span></span> 
</p>
<p>
<span style="font-family:宋体;font-size:24px;">【输入输出样例】</span> 
</p>
<p>
<b><span style="font-size:18px;">(checker.in)</span></b> 
</p>
<p>
<span style="font-size:18px;"><span style="font-size:18px;">6</span></span> 
</p>
<p>
<b><span style="font-size:18px;">(checker.out)</span></b> 
</p>
<p>
<span style="font-size:18px;"><span style="font-size:18px;">2 4 6 1 3 5</span></span> 
</p>
<p>
<span style="font-size:18px;"><span style="font-size:18px;">3 6 2 5 1 4</span></span> 
</p>
<p>
<span style="font-size:18px;"><span style="font-size:18px;">4 1 5 2 6 3</span></span> 
</p>
<p>
<span style="font-size:18px;"><span style="font-family:宋体;font-size:18px;">4</span></span> 
</p>
