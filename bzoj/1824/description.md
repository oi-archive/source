
# Description

<div class="content"> JYY发明了一个新的益智游戏，该游戏由A和B 兩人轮流在一个1,000,000x 1,000,000 的方格棋盘上的网格线交点下棋，网格线交点的坐标以（x, y）表示之（ 0 &lt; = x , y &lt; =1,000,000），(0, 0)代表棋盘最左下角的点。
每一个棋子放置的位置不可以与任何其它棋子在同一X 坐标或Y 坐标上，棋盘上新增加一个棋子时，棋盘上的计数器会自动算出以目前棋盘上棋子所能够围成的「无障碍四方形」个数。
「无障碍四方形」是指以任意兩个棋子所定义出的四方形内部不含其它棋子，每下一个棋子后所算出的「无障碍四方形」个数即为下该棋子的得分數。每位下棋者的总分即是该下棋者每个所下棋子的得分数总和。
请写一个程序计算A 和 B 兩位下棋者的累计总分。

</div>

# Input

<div class="content">第一行输入只有一个整数 n，代表此盘棋共下了n (1 &lt; = n &lt; = 5,000)个棋子。接下來的n 行，每一行有兩个整数，依序代表这n 个棋子所放置的位置。
请注意，由于测试资料中有可能包含n=1000 的输入，你的程序必须非常的有效率才会通过所有的测试资料。

</div>

# Output

<div class="content">请输出兩个整数，分别代表该盘棋兩位下棋者的累计得分數。先下棋者(A)的分数在前，后下棋者(B)的分数在后，中间用一个空格隔开。

</div>

# Sample Input

<div class="content"><span class="sampledata">4      <br/>
2  3    <br/>
3  4    <br/>
1  2    <br/>
4  1    <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2  6    <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JSOI2010第二轮Contest2">JSOI2010第二轮Contest2</a></p></div>

