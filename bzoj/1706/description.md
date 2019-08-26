
# Description

<div class="content"><p><span style="font-size: medium">FJ的N(2 &lt;= N &lt;= 1,000,000)头奶牛选择了接力跑作为她们的日常锻炼项目。至于进行接力跑的地点 自然是在牧场中现有的T(2 &lt;= T &lt;= 100)条跑道上。 农场上的跑道有一些交汇点，每条跑道都连结了两个不同的交汇点 I1_i和I2_i(1 &lt;= I1_i &lt;= 1,000; 1 &lt;= I2_i &lt;= 1,000)。每个交汇点都是至少两条跑道的端点。 奶牛们知道每条跑道的长度length_i(1 &lt;= length_i &lt;= 1,000)，以及每条跑道连结的交汇点的编号 并且，没有哪两个交汇点由两条不同的跑道直接相连。你可以认为这些交汇点和跑道构成了一张图。 为了完成一场接力跑，所有N头奶牛在跑步开始之前都要站在某个交汇点上（有些交汇点上可能站着不只1头奶牛）。当然，她们的站位要保证她们能够将接力棒顺次传递，并且最后持棒的奶牛要停在预设的终点。 你的任务是，写一个程序，计算在接力跑的起点(S)和终点(E)确定的情况下，奶牛们跑步路径可能的最小总长度。显然，这条路径必须恰好经过N条跑道。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 4个用空格隔开的整数：N，T，S，以及E </span></p>
<p><span style="font-size: medium">* 第2..T+1行: 第i+1为3个以空格隔开的整数：length_i，I1_i，以及I2_i， 描述了第i条跑道。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出1个正整数，表示起点为S、终点为E，并且恰好经过N条跑道的路 径的最小长度 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 6 6 4<br/>
11 4 6<br/>
4 4 8<br/>
8 4 9<br/>
6 6 8<br/>
2 6 9<br/>
3 8 9<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

