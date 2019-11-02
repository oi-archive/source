<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个矩形房间，覆盖正方形瓷砖。每块瓷砖涂成了红色或黑色。一名男子站在黑色的瓷砖上，由此出发，可以移到四个相邻瓷砖之一，但他不能移动到红砖上，只能移动到黑砖上。编写一个程序，计算他通过重复上述移动所能经过的黑砖数。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包含多个数据集。一个数据集开头行包含两个正整数W和H，W和H分别表示矩形房间的列数和行数，且都不超过20.<br>每个数据集有H行，其中每行包含W个字符。每个字符的含义如下所示：<br>'.'——黑砖<br>'#'——红砖<br>'@'——男子（每个数据集仅出现一次）<br>两个0表示输入结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每个数据集，程序应该输出一行，包含男子从初始瓷砖出发可到达的瓷砖数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 9<br>....#.<br>.....#<br>......<br>......<br>......<br>......<br>......<br>#@...#<br>.#..#.<br>11 9<br>.#.........<br>.#.#######.<br>.#.#.....#.<br>.#.#.###.#.<br>.#.#..@#.#.<br>.#.#####.#.<br>.#.......#.<br>.#########.<br>...........<br>11 6<br>..#..#..#..<br>..#..#..#..<br>..#..#..###<br>..#..#..#@.<br>..#..#..#..<br>..#..#..#..<br>7 7<br>..#.#..<br>..#.#..<br>###.###<br>...@...<br>###.###<br>..#.#..<br>..#.#..<br>0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>45<br>59<br>6<br>13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>