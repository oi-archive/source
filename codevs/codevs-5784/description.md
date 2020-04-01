<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>题目背景(可以不看):<br></p><p>《2048》是一款比较流行的数字游戏，最早于2014年3月20日发行。原版2048首先在GitHub上发布，原作者是Gabriele
Cirulli，后被移植到各个平台。(摘自百度百科)
小鸟想要写一个2048的AI，它研究了几天启发式搜索，max-avg，αβ剪枝....终于一切都搞明白了，但还没有一个可用的2048程序，于是它想让你帮忙来写。实际上，2048是一个模拟核反应堆的程序，它模拟向反应堆中随机添加粒子，当两个粒子之间满足某种超过临界质量的关系，两个粒子就会合并成一个粒子(大雾</p><p>题目描述:<br></p><p>小鸟想要研究的是标准版的2048，规则是这样的:游戏在4*4的正方形棋盘上进行，开始时棋盘为空，分数为0。首先系统会随机生成两个数字在棋盘的任意位置。然后每次可以选择上下左右其中一个方向去滑动，每滑动一次，所有的数字方块都会往滑动的方向靠拢外，系统也会在空白的地方随机出现一个数字方块(只能是2或4)，相同数字的方块在靠拢、相撞时会相加，并获得与合并后的数字大小相等的分数。如果某次移动操作后，棋盘上所有数字和数字的位置与原来相同，并且分数不变，则不进行此次移动操作。具体移动和合并的方式请看样例。<br>现在给你n步操作，由2个或4个字符组成。第一个是'M'或'P',分别表示移动和放置数字。如果第一个字符是'M'，则第二个字符为数字0~3，分别代表向上下左右四个方向移动，没有第三个字符。如果第一个字符是'P'，则后面三个字符i,j,k分别表示在第i行，第j列放置一个数字k(左上角为第0行第0列，右下角为第3行第3列)，0&lt;=i,j&lt;3.k=2或4。<br>初始时棋盘为空，分数为0，你需要模拟这n步操作，并输出所有操作进行完后的局面和分数。(输入保证执行放置数字操作时，指定的位置一定为空)<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数n<br>接下来n行每行表示一个操作，格式见题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行为进行完所有操作后的最终分数<br/>接下来4行，每行4个数字，第i行第j个数字表示进行完所有操作后，棋盘上第i行，第j列的数字方块。<br/>如果某位置没有数字，用0表示。<br/>每一行中的4个数字之间用空格隔开</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>样例1:
6
P 1 2 2
P 2 2 4
P 3 2 2
P 0 2 4
P 1 0 2
M 2</pre><pre>样例2:
17
P 0 0 2
P 0 1 2
P 0 2 4
P 0 3 2
P 1 0 2
P 1 1 2
P 1 2 2
P 1 3 2
P 2 0 2
P 2 1 2
P 2 2 2
P 2 3 4
P 3 0 2
P 3 1 2
P 3 2 2
P 3 3 2
M 0</pre><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>样例1:
4
4 0 0 0
4 0 0 0
4 0 0 0
2 0 0 0

样例2:
24
4 4 4 4
4 4 4 4
0 0 2 2
0 0 0 0</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=1000<br>要求放置的数字只有2或者4</p><p><br></p><p>如果还是看不懂移动方法，可以在这个网站亲自试一试<br>&lt;a href="http://gabrielecirulli.github.io/2048/"&gt;http://gabrielecirulli.github.io/2048/&lt;/a&gt;</p><p><br></p>
</div>
</div>