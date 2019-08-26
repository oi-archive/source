
# Description

<div class="content">三只狼和一只羊在一片草地上相遇了~ 群狼很饥饿,后果很严重……
草地是一个R*C的矩形，矩形内“X”点代表石头是不能过的，“.”代表草地。狼用“W”表示，羊用“S”表示。
狼和羊交替的走，轮到狼走的时候，可以选择3只中的任意一只走一步，如果三只狼都走不动，那么可以不走。轮到羊走的时候，羊必须走。
如果某个时候羊不能走了，即它被围住了，那么羊就要被吃掉了，否则的话如果它逃出了草地，那么它就得救了。狼想知道他们能不能在有限步内围住羊然后美餐一顿。

</div>

# Input

<div class="content">首先两个数R,C
接下来一个R*C的矩阵描述草地。
多组数据，处理到文件尾。

</div>

# Output

<div class="content">如果狼能围住羊，打印danger，否则打印safe。

</div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
..X.X<br/>
W..X.<br/>
....W<br/>
.SWX.<br/>
<br/>
5 5<br/>
..WXS<br/>
W.WXX<br/>
...X.<br/>
.XX..<br/>
..X.X<br/>
<br/>
4 4<br/>
.WW.<br/>
...S<br/>
.XX.<br/>
..W.<br/>
<br/>
4 4<br/>
S..W<br/>
X.X.<br/>
....<br/>
..WW<br/>
<br/>
5 5<br/>
...W.<br/>
.X...<br/>
XW..X<br/>
..S.X<br/>
.W...<br/>
<br/>
5 5<br/>
XXXXX<br/>
X...X<br/>
XXW.X<br/>
XWWSX<br/>
XXXXX<br/>
<br/>
5 4<br/>
X.W.<br/>
SXXW<br/>
..X.<br/>
.W..<br/>
X...<br/>
<br/>
4 5<br/>
XXXXX<br/>
XS.WX<br/>
XWW.X<br/>
XXXXX<br/>
<br/>
5 4<br/>
..X.<br/>
..X.<br/>
..X.<br/>
WX.S<br/>
W.W.<br/>
<br/>
4 5<br/>
XXXXX<br/>
XW.SX<br/>
X.WWX<br/>
XXXXX<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">safe<br/>
safe<br/>
safe<br/>
safe<br/>
safe<br/>
danger<br/>
safe<br/>
danger<br/>
safe<br/>
danger<br/>
</span></div>

# Hint

<div class="content"><p><br/>
对于40%的数据保证 <br/>
对于100%的数据保证 <br/>
数据组数小于等于10。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

