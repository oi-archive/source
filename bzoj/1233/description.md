
# Description

<div class="content"><p>奶牛们讨厌黑暗。 为了调整牛棚顶的电灯的亮度，Bessie必须建一座干草堆使得她能够爬上去够到灯泡 。一共有N大包的干草（1&lt;=N&lt;=100000）(从1到N编号)依靠传送带连续的传输进牛棚来。第i包干草有一个 宽度W_i(1&lt;=w_i&lt;=10000)。所有的干草包的厚度和高度都为1. Bessie必须利用所有N包干草来建立起干草堆，并且按照他们进牛棚的顺序摆放。她可以相放多少包就放 多少包来建立起tower的地基（当然是紧紧的放在一行中）。接下来他可以放置下一个草包放在之前一级 的上方来建立新的一级。注意：每一级不能比下面的一级宽。她持续的这么放置，直到所有的草包都被安 置完成。她必须按顺序堆放，按照草包进入牛棚的顺序。说得更清楚一些：一旦她将一个草包放在第二级 ，她不能将接下来的草包放在地基上。 Bessie的目标是建立起最高的草包堆。</p></div>

# Input

<div class="content"><p>第1行：一个单一的整数N。 第2~N+1行：一个单一的整数:W_i。</p></div>

# Output

<div class="content"><p>第一行：一个单一的整数，表示Bessie可以建立的草包堆的最高高度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
2<br/>
3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
输出说明：<br/>
前两个（宽度为1和2的）放在底层，总宽度为3，在第二层放置宽度为3的。<br/>
           +----------+<br/>
           |    3     |<br/>
           +---+------+<br/>
           | 1 |   2  |<br/>
           +---+------+<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=
"><br/>
</a></p></div>

