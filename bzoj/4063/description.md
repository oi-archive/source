
# Description

<div class="content"><p>考虑一个扔飞镖的游戏。板子由十个环组成，半径分别为20, 40, 60, 80, 100, 120, 140, 160, 180和200（单位：mm），均以原点为中心。每次投掷的得分取决于飞镖所击中的位置。如果包含飞镖的最小环（可以在圆上）的半径是20 * (11 - p)，则得分是p。不在最外环以内的点不得分。你的任务是计算n次投掷之后的得分。</p></div>

# Input

<div class="content"><p>第一行一个正整数T，表示有T组数据。</p>
<div>
<div>每组数据第一行一个正整数n，表示有n次投掷，1 &lt;= n &lt;= 10^6。</div>
<div>接下来n行，每行两个整数x和y，表示一次投掷击中的位置为(x, y)，-200 &lt;= x, y &lt;= 200。</div>
</div></div>

# Output

<div class="content"><p>对于每组数据输出一行，即n次投掷得分的总和。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5<br/>
32 -39<br/>
71 89<br/>
-60 80<br/>
0 0<br/>
196 89  <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">29<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

