# 题目描述


<div>
USACO/shuttleus(译by Jeru)
<hr/>
</div>
<p>
描述
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">大小为3的棋盘游戏里有3个白色棋子，3个黑色棋子，和一个有7个格子一线排开的木盒子。3个白棋子被放在一头，3个黑棋子被放在另一头，中间的格子空着。 <br/>
<br/>
初始状态: WWW_BBB <br/>
目标状态: BBB_WWW<br/>
<br/>
在这个游戏里有两种移动方法是允许的：<br/>
1. 你可以把一个棋子移到与它相邻的空格；<br/>
2. 你可以把一个棋子跳过一个(仅一个)与它不同色的棋子到达空格。 <br/>
<br/>
大小为N的棋盘游戏包括N个白棋子，N个黑棋子，还有有2N+1个格子的木盒子。 <br/>
<br/>
这里是3-棋盘游戏的解，包括初始状态，中间状态和目标状态： <br/>
<br/>
WWW BBB<br/>
WW WBBB<br/>
WWBW BB<br/>
WWBWB B<br/>
WWB BWB<br/>
W BWBWB<br/>
 WBWBWB<br/>
BW WBWB<br/>
BWBW WB<br/>
BWBWBW <br/>
BWBWB W<br/>
BWB BWW<br/>
B BWBWW<br/>
BB WBWW<br/>
BBBW WW<br/>
BBB WWW<br/>
<br/>
<br/>
请编一个程序解大小为N的<b>棋盘游戏</b>(1 &lt;= N &lt;= 12)。要求用最少的移动步数实现。</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<br/>
</p>
<p>
<b><span style="font-family:&#39;Times New Roman&#39;;font-size:medium;">PROGRAM NAME: shuttleus</span></b> 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file shuttleus.in)<br/>
</span> 
</h3>
<span style="font-family:&#39;Times New Roman&#39;;"> 
<p>
<br/>
一个整数N。
</p>
<p>
 
</p>
<span style="font-family:&#39;Times New Roman&#39;;"></span> 
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><b><span style="font-size:medium;">OUTPUT FORMAT(file shuttleus.out)</span></b><br/>
用空格在棋盘的位置(位置从左到右依次为1, 2, ..., 2N+1)表示棋盘的状态。输出棋盘的状态变换序列，每行20个数(除了最后一行)。 <br/>
<br/>
输出的解还应当有最小的字典顺序(即如果有多组移动步数最小的解，输出第一个数最小的解；如果还有多组，输出第二个数最小的解；...)。 </span> 
</p>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><b><span style="font-size:medium;">SAMPLE INPUT (file shuttleus.in)</span></b><br/>
3</span> 
</p>
<span style="font-family:&#39;Times New Roman&#39;;"></span> 
<p>
<br/>
</p>
<span style="font-family:&#39;Times New Roman&#39;;"><b><span style="font-size:medium;">SAMPLE OUTPUT (file shuttleus.out)</span></b><br/>
3 5 6 4 2 1 3 5 7 6 4 2 3 5 4<br/>
<br/>
</span> 
<p>
 
</p>
</span>
