
# Description

<div class="content">Task: Tetris 3D

&#34;Tetris&#34; 游戏的作者决定做一个新的游戏, 一个三维的版本, 在里面很多立方体落在平面板,一个立方体开始落下直到碰上一个以前落下的立方体或者落地即停止. 
作者想改变一下游戏的目的使得它更大众化,在新游戏中你将知道落下的立方体信息以及位置,你的任务就是回答所有立方体落下后最高的方块的高度.所有的立方体在下落过程中都是垂直的并且不会旋转.平板左下角坐标为原点,并且平行于坐标轴. 
</div>

# Input

<div class="content">第一行给出三个整数 D, S and N ( 1&lt;= N&lt;= 20 000, 1&lt;= D, S &lt;=1 000), 分别表示平板的长和宽以及下落立方体的数目. 接下来N 行每行描述一个立方体. 
每行包含5个整数: d, s, w, x and y (1&lt;= d, 0 &lt;=x, d + x&lt;= D, 1 &lt;=s, 0&lt;= y, s + y&lt;= S, 1&lt;= w &lt;=100 000), 分别表示立方体的长\宽\高以及落下的左下角坐标, 长和宽都是平行于平板坐标轴的,落下后立方体着地的四个角坐标分别为: (x, y), (x + d, y), (x, y + s) and (x + d, y + s). 
</div>

# Output

<div class="content">一个整数表示所有立方体落下后最高的方块的高度.
</div>

# Sample Input

<div class="content"><span class="sampledata">7 5 4<br/>
4 3 2 0 0<br/>
3 3 1 3 0<br/>
7 1 2 0 3<br/>
2 3 3 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

