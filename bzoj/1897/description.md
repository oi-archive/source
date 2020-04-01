
# Description

<div class="content">有这样一款新的坦克游戏。在游戏中，你将操纵一辆坦克，在一个N×M的区域中完成一项任务。在此的区域中，将会有许多可攻击的目标，而你每摧毁这样的一个目标，就将获得与目标价值相等的分数。只有获得了最高的分数，任务才算完成。同时，为了增加游戏的真实性和难度，该游戏还做了以下的限制：
1)坦克有射程r的限制。为方便计算，射程r规定为：若坦克位于(x, y)格，则它可攻击的目标(x1, y1)必须满足|x-x1|, |y-y1|∈[0, r]。
2)对坦克完成任务的时间有严格限制，规定为t秒。其中，坦克每进行一次移动都需1秒的时间，每攻击一个目标也需1秒的时间。时间一到t秒，便对此次任务进行记分。
3)坦克最初位于左上角，且移动方向只准是向右或向下，每次只允许移动一格。
在以上的限制条件下，要完成该任务便成为了一件很难事情。因此，你必须为此编写一个程序，让它助你完成这个艰巨的任务。

</div>

# Input

<div class="content">第一行四个整数N、M、r、t，分别表示区域的长、宽，以及射程和完成任务时间。
接下来N行是一个N×M的矩阵，对应每个位置上目标的价值。

</div>

# Output

<div class="content">输出文件仅一个数max，即该任务中可得到的最高分数。

</div>

# Sample Input

<div class="content"><span class="sampledata">5 5 2 7<br/>
0 5 0 0 4<br/>
0 0 0 0 2<br/>
0 0 0 0 0<br/>
0 0 0 0 0<br/>
5 0 3 0 11<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">21<br/>
</span></div>

# Hint

<div class="content"><p>1≤N、M≤500，1≤r≤100，1≤t≤250。<br/>
对于20%的数据有：1≤N、M≤10。<br/>
对于60%的数据有：1≤N、M≤50，1≤r≤10。<br/>
对于80%的数据有：1≤N、M≤100，1≤r≤20。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=modi from Zju2649 The Brave Tankman">modi from Zju2649 The Brave Tankman</a></p></div>

