# 题目描述


<p>
<b><span style="font-family:Microsoft YaHei;font-size:18px;">Problem 4 : unique</span></b> 
</p>
<p>
<b><span style="font-family:Microsoft YaHei;font-size:18px;">寻找代表元</span></b> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> <img src="/upload/image/20131205/20131205212219_65812.jpg" alt=""/></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">问题描述</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">八中一共有</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">个社团，分别用</span><span style="font-family:Microsoft YaHei;font-size:18px;">1</span><span style="font-family:Microsoft YaHei;font-size:18px;">到</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">编号。</span></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">八中一共有</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">个人，分别用</span><span style="font-family:Microsoft YaHei;font-size:18px;">1</span><span style="font-family:Microsoft YaHei;font-size:18px;">到</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">编号。每个人可以参加一个或多个社团，也可以不参加任何社团。</span></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">每个社团都需要选一个代表。我们希望更多的人能够成为代表。这里，每个人至多代表一个社团且每个社团至多有一个代表。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输入数据</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">第一行输入两个数</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">和</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">。</span></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">以下</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">行每行若干个数，这些数都是不超过</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">的正整数。其中第</span><span style="font-family:Microsoft YaHei;font-size:18px;">i</span><span style="font-family:Microsoft YaHei;font-size:18px;">行的数表示社团</span><span style="font-family:Microsoft YaHei;font-size:18px;">i</span><span style="font-family:Microsoft YaHei;font-size:18px;">的全部成员。每行用一个</span><span style="font-family:Microsoft YaHei;font-size:18px;">0</span><span style="font-family:Microsoft YaHei;font-size:18px;">结束。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输出数据</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">输出最多的能够成为代表的人数。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">样例输入</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">4
4</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1
2 0</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1
2 0</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1
2 0</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1
2 3 4 0</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">样例输出</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">3</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">数据范围</span><span style="font-family:&#34;"></span> 
</p>
<p style="text-indent:21.75pt;">
<span style="font-family:Microsoft YaHei;font-size:18px;">n,m&lt;=200</span> 
</p>
