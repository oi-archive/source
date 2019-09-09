# 题目描述


<div>
USACO/bigbrn(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
农夫约翰想要在他的正方形农场上建造一座正方形大牛棚。他讨厌在他的农场中砍树，想找一个能够让他在空旷无树的地方修建牛棚的地方。我们假定，他的农场划分成 N x N 的方格。输入数据中包括有树的方格的列表。你的任务是计算并输出，在他的农场中，不需要砍树却能够修建的最大正方形牛棚。牛棚的边必须和水平轴或者垂直轴平行。
<h3>
EXAMPLE
</h3>
<p>
考虑下面的方格，它表示农夫约翰的农场，‘.&#39;表示没有树的方格，‘#&#39;表示有树的方格
</p>
<pre>          1 2 3 4 5 6 7 8
        1 . . . . . . . .
        2 . # . . . # . .
        3 . . . . . . . .
        4 . . . . . . . .
        5 . . . . . . . .
        6 . . # . . . . .
        7 . . . . . . . .
        8 . . . . . . . .</pre>
<p>
最大的牛棚是 5 x 5 的，可以建造在方格右下角的两个位置其中一个。
</p>
<h3>
PROGRAM NAME: bigbrn
</h3>
<h3>
INPUT FORMAT(file bigbrn.in)
</h3>
<table border="1">
<tbody>
<tr>
<td>
Line 1:
</td>
<td>
两个整数： N （1 &lt;= N &lt;= 1000），农场的大小，和 T （1 &lt;= T &lt;= 10，000）有树的方格的数量
</td>
</tr>
<tr>
<td>
Lines 2..T+1:
</td>
<td>
两个整数（1 &lt;= 整数 &lt;= N), 有树格子的横纵坐标
</td>
</tr>
</tbody>
</table>
<h3>
OUTPUT FORMAT(file bigbrn.out)
</h3>
<p>
输出文件只由一行组成，约翰的牛棚的最大边长。
</p>
<h3>
SAMPLE INPUT (file bigbrn.in)
</h3>
<p>
8 3<br/>
2 2<br/>
2 6<br/>
6 3
</p>
<h3>
SAMPLE OUTPUT (file bigbrn.out)
</h3>
5
<p>
 
</p>
