# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«问题描述：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">机器人Rob可在一个树状路径上自由移动。给定树状路径T上的起点s 和终点t，机器</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">人Rob要从s运动到t。树状路径T上有若干可移动的障碍物。由于路径狭窄，任何时刻在</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">路径的任何位置不能同时容纳2 个物体。每一步可以将障碍物或机器人移到相邻的空顶点</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">上。设计一个有效算法用最少移动次数使机器人从s运动到t。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«编程任务：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于给定的树T，以及障碍物在树T中的分布情况。计算机器人从起点s 到终点t的最</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">少移动次数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«数据输入：</span><br/>
<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">由文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">robotpath.in</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">提供输入数据。文件的第1 行有3 个正整数n，s和t，分别表示树T的</span></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">顶点数，起点s的编号和终点t 的编号。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来的n 行分别对应于树T 中编号为0，1，…，n-1 的顶点。每行的第1 个整数h</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示顶点的初始状态，当h=1 时表示该顶点为空顶点，当h=0 时表示该顶点为满顶点，其</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">中已有1 个障碍物。第2 个数k表示有k个顶点与该顶点相连。接下来的k个数是与该顶点</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">相连的顶点编号。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«结果输出：</span><br/>
<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">程序运行结束时，将计算出的机器人最少移动次数输出到文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">robotpath.out</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 中。如果无法</span></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">将机器人从起点移动到终点，输出“No solution！”。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件示例 输出文件示例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>robotpath.in</span></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5 0 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3 0 1 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0 2 2 4</span><br/>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1 3</span> 
</p>
<p>
<span style="font-family:&#34;">robotpath.out</span> 
</p>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">保证输入的所有数小于等于1000</span> 
</p>
