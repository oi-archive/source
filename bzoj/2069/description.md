
# Description

<div class="content">在Byte山的山脚下有一个洞穴入口. 这个洞穴由复杂的洞室经过隧道连接构成. 洞穴的入口是一条笔直通向“前面洞口”的道路. 隧道互相都不交叉(他们只在洞室相遇). 两个洞室要么就通过隧道连接起来,要么就经过若干隧道间接的相连. 
现在决定组织办一个&#39;King&#39;s of Byteotia Cup&#39; 比赛. 参赛者的目标就是任意选择一条路径进入洞穴并尽快出来即可. 一条路径必须经过除了“前面洞口”之外还至少要经过其他一个洞室.一条路径中一个洞不能重复经过(除了“前面洞室”以外),类似的一条隧道也不能重复经过.
一个著名的洞穴探险家 Byteala 正准备参加这个比赛. Byteala 已经训练了数月而且他已获得了洞穴系统的一套详细资料. 对于每条隧道他都详细计算了从两个方向经过所需要的时间. 经过一个洞室的时间很短可以忽略不记. 现在Byteala 向计算一条符合条件的最优路径.
</div>

# Input

<div class="content">第一行有两个数n 和 m (3 &lt;= n &lt;= 5000, 3 &lt;= m &lt;= 10000) 分别表示洞室的数目以及连接他们的隧道的数目. 洞室从1 到 n编号. “前面洞室”的编号为1. 接下来m 行描述了所有的隧道. 每行四个整数a,b,c,d 表示从洞室a到洞室b需要c分钟的时间,而从洞室b到洞室a需要d分钟的时间, 1 &lt;= a,b &lt;= n, a &lt;&gt; b, 1 &lt;= c,d &lt;= 10000. 你可以假设符合要求的路径肯定存在.
</div>

# Output

<div class="content">输出一行,最少需要多少时间完成比赛.
</div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 4 3<br/>
2 3 4 2<br/>
1 3 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Stage 1">Stage 1</a></p></div>

