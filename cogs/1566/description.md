# 题目描述


<h3>
【中文题意】
</h3>
<p>
一些蚂蚁以1cm/s的速度在长度为Lcm的水平杆上爬行，爬到端点就会掉下去。当两只蚂蚁相遇，它们就会立刻掉头返回。已知L和一开始每只蚂蚁的位置，但不知道它们的方向，求它们最早何时全部掉落，最迟何时全部掉落。
</p>
<p>
最多1,000,000只蚂蚁。
</p>
<h3>
【题目描述】
</h3>
<p>
<img alt="" src="/upload/image/20140328/20140328205759_83378.jpg"/> 
</p>
<div class="ptx" lang="zh-CN">
An army of ants walk on a horizontal pole of length l cm, each with a constant speed of 1 cm/s. When a walking ant reaches an end of the pole, it immediatelly falls off it. When two ants meet they turn back and start walking in opposite directions. We know the original positions of ants on the pole, unfortunately, we do not know the directions in which the ants are walking. Your task is to compute the earliest and the latest possible times needed for all ants to fall off the pole.
</div>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有一个整数，代表数据组数。
</p>
<p>
接下来有若干组数据。
</p>
<p>
每组数据的第一行有两个整数：水平杆的长度（单位：cm）和杆上蚂蚁的数量。
</p>
<p>
接下来有n个整数，给出了每只蚂蚁最初的位置，即杆的左端点到蚂蚁位置的距离。不一定按顺序给出。
</p>
<p>
所有的输入不超过1000000，整数之间由空格分隔。
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，输出两个空格隔开的整数。
</p>
<p>
第一个整数是全部蚂蚁掉下杆的最早可能时间（如果恰当地选择它们的移动方向）。第二个整数是全部蚂蚁掉下杆的最晚可能时间。
</p>
<h3>
【样例输入】
</h3>
<pre class="sio">2
10 3
2 6 7
214 7
11 12 7 13 176 23 191
</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">4 8
38 207
</pre>
<h3>
【来源】
</h3>
<p>
<a href="http://poj.org/problem?id=1852">北京大学 POJ 1852</a> 
</p>
<h3>
【提示】
</h3>
<p>
<span style="font-size:16px;">horizontal pole 水平杆</span> 
</p>
<p>
<span style="font-size:16px;">constant speed 恒速</span> 
</p>
