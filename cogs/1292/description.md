# 题目描述


<h3>
【题目描述】
</h3>
<p>
在一个凹槽中放置了n层砖块，最上面的一层有n块砖，第二层有n-1块，……最下面一层仅有一块砖。第i层的砖块从左至右编号为1，2，……i，第i层的第j块砖有一个价值a[i,j]（a[i,j]&lt;=50）。下面是一个有5层砖块的例子：
</p>
<p>
<img src="/upload/image/20130109/20130109175950_80635.png" alt=""/> 
</p>
<p>
如果你要敲掉第i层的第j块砖的话，若i=1，你可以直接敲掉它，若i&gt;1，则你必须先敲掉第i-1层的第j和第j+1块砖。
</p>
<p>
你的任务是从一个有n（n&lt;=50）层的砖块堆中，敲掉(m&lt;=500)块砖，使得被敲掉的这些砖块的价值总和最大。
</p>
<h3>
【输入格式】
</h3>
<p>
你将从文件中读入数据，数据的第一行为两个正整数，分别表示n,m，接下来的第i每行有n-i+1个数据，分别表示a[i,1],a[i,2]……a[i,n – i + 1]。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件中仅有一个正整数，表示被敲掉砖块的最大价值总和。
</p>
<h3>
【样例输入】
</h3>
<pre>4 5
2 2 3 4
8 2 7
2 3
49
</pre>
<h3>
【样例输出】
</h3>
<pre>19
(敲掉第一层的四块砖，再敲掉第二层的第一块砖，2+2+3+4+8=19)</pre>
<h3>
【提示】
</h3>
<p>
运行时限：1秒钟
</p>
<p>
本题目一共有十个测试点，每个测试点的分数为总分数的10%。对于每个测试点来说，如果你给出的答案正确，那么你将得到该测试点全部的分数，否则得0分。
</p>
