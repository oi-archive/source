
# Description

<div class="content"><div><span style="font-size: medium">这天，SJY显得无聊。在家自己玩。在一个棋盘上，有N个黑色棋子。他每次要么放到棋盘上一个黑色棋子，要么放上一个白色棋子，如果是白色棋子，他会找出距离这个白色棋子最近的黑色棋子。此处的距离是 曼哈顿距离 即(|x1-x2|+|y1-y2|) 。现在给出N&lt;=500000个初始棋子。和M&lt;=500000个操作。对于每个白色棋子，输出距离这个白色棋子最近的黑色棋子的距离。同一个格子可能有多个棋子。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行两个数 N M </span></div>
<div><span style="font-size: medium">以后M行，每行3个数 t x y</span></div>
<div><span style="font-size: medium">如果t=1 那么放下一个黑色棋子</span></div>
<div><span style="font-size: medium">如果t=2 那么放下一个白色棋子</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">对于每个T=2 输出一个最小距离</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
1 1<br/>
2 3<br/>
2 1 2<br/>
1 3 3<br/>
2 4 2<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
1<br/>
2<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p> <br/><br/>
kdtree可以过</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 孙嘉裕">鸣谢 孙嘉裕</a></p></div>

