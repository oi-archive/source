# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">设有<span>n</span><span>个大小不等的中空圆盘，按从小到大的顺序从</span><span>1</span><span>到</span><span>n</span><span>编号。将这</span><span>n</span><span>个圆盘任意的迭套在三根立柱上，立柱的编号分别为</span><span>A</span><span>、</span><span>B</span><span>、</span><span>C</span><span>，这个状态称为初始状态。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    现在要求找到一种步数最少的移动方案，使得从初始状态转变为目标状态。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    移动时有如下要求：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    ·一次只能移一个盘；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    ·不允许把大盘移到小盘上面。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
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
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">文件第一行是状态中圆盘总数；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第二到第四行分别是初始状态中<span>A</span><span>、</span><span>B</span><span>、</span><span>C</span><span>柱上圆盘的个数和从上到下每个圆盘的编号；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第五到第七行分别是目标状态中<span>A</span><span>、</span><span>B</span><span>、</span><span>C</span><span>柱上圆盘的个数和从上到下每个圆盘的编号。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">每行一步移动方案，格式为：<span>move I from P to Q</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">最后一行输出最少的步数。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>5
3 3 2 1
2 5 4
0
1 2
3 5 4 3
1 1</pre>
<h3>
【样例输出】
</h3>
<pre>move 1 from A to B
move 2 from A to C
move 1 from B to C
move 3 from A to B
move 1 from C to B
move 2 from C to A
move 1 from B to C
7
</pre>
