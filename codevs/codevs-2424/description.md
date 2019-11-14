<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>是不是平时在手机里玩吃豆豆游戏玩腻了呢？最近MOKIA手机上推出了一种新的围豆豆游戏，大家一起来试一试吧。</p>
<p> </p>
<p>游戏的规则非常简单，在一个<em>N</em>×<em>M</em>的矩阵方格内分布着<em>D</em>颗豆子，每颗豆有不同的分值<em>V<sub>i</sub></em>。游戏者可以选择任意一个方格作为起始格，每次移动可以随意的走到相邻的四个格子，直到最终又回到起始格。<strong>最终游戏者的得分为所有被路径围住的豆豆的分值总和减去游戏者移动的步数。</strong>矩阵中某些格子内设有障碍物，任何时刻游戏者不能进入包含障碍物或豆子的格子。游戏者可能的最低得分为0，即什么都不做。</p>
<p> </p>
<p>注意路径包围的概念，即某一颗豆在路径所形成的多边形（可能是含自交的复杂多边形）的内部。下面有两个例子：</p>
<p>第一个例子中，豆在路径围成的矩形内部，所以豆被围住了。第二个例子中，虽然路径经过了豆的周围的8个格子，但是路径形成的多边形内部并不包含豆，所以没有围住豆子。</p>
<p>布布最近迷上了这款游戏，但是怎么玩都拿不了高分。聪明的你决定写一个程序来帮助他顺利通关。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数<em>N</em>和<em>M</em>，为矩阵的边长。</p>
<p>第二行一个整数<em>D</em>，为豆子的总个数。</p>
<p>第三行包含<em>D</em>个整数<em>V</em><sub>1</sub>到<em>V<sub>D</sub></em>，分别为每颗豆子的分值。</p>
<p>接着<em>N</em>行有一个<em>N</em>×<em>M</em>的字符矩阵来描述游戏矩阵状态，0表示空格，#表示障碍物。而数字1到9分别表示对应编号的豆子。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个整数，为最高可能获得的分值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 8</p>
<p>3</p>
<p>30 -100 30</p>
<p>00000000</p>
<p>010203#0</p>
<p>00000000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>38</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足1≤<em>D</em>≤3。</p>
<p>100%的数据满足1≤<em>D</em>≤9，1≤<em>N</em>, <em>M</em>≤10，-10000≤<em>V<sub>i</sub></em>≤10000。</p>
</div>
</div>