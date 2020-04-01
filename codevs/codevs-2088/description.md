<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>大小为3的棋盘游戏里有3个白色棋子，3个黑色棋子，和一个有7个格子一线排开的木盒子。3个白棋子被放在一头，3个黑棋子被放在另一头，中间的格子空着。</p>
<pre>初始状态: WWW_BBB
目标状态: BBB_WWW
</pre>
<p>在这个游戏里有两种移动方法是允许的：</p>
<ol>
<li>你可以把一个棋子移到与它相邻的空格；</li>
<li>你可以把一个棋子跳过一个(仅一个)与它不同色的棋子到达空格。</li>
</ol>
<p>大小为N的棋盘游戏包括N个白棋子，N个黑棋子，还有有2N+1个格子的木盒子。</p>
<p>这里是3-棋盘游戏的解，包括初始状态，中间状态和目标状态：</p>
<pre> WWW BBB
WW WBBB
WWBW BB
WWBWB B
WWB BWB
W BWBWB
WBWBWB
BW WBWB
BWBW WB
BWBWBW
BWBWB W
BWB BWW
B BWBWW
BB WBWW
BBBW WW
BBB WWW
</pre>
<p>请编一个程序解大小为N的棋盘游戏(1 &lt;= N &lt;= 12)。要求用最少的移动步数实现。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一个整数N。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出用移动的棋子在棋盘的位置(位置从左到右依次为1, 2, ..., 2N+1)表示的变换序列，每个数字之间以空格分隔，每行20个数(除了最后一行)。</p>
<p>输出的解还应当有最小的字典顺序(即如果有多组移动步数最小的解，输出第一个数最小的解；如果还有多组，输出第二个数最小的解；...)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>3 5 6 4 2 1 3 5 7 6 4 2 3 5 4</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>