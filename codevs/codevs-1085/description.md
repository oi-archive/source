<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">丁丁最近沉迷于一个数字游戏之中。这个游戏看似简单，但丁丁在研究了许多天之后却发觉原来在简单的规则下想要赢得这个游戏并不那么容易。游戏是这样的，在你面前有一圈整数（一共<span style="font-family: DejaVu Serif Condensed,serif;">n</span>个），你要按顺序将其分为<span style="font-family: DejaVu Serif Condensed,serif;">m</span>个部分，各部分内的数字相加，相加所得的<span style="font-family: DejaVu Serif Condensed,serif;">m</span>个结果对<span style="font-family: DejaVu Serif Condensed,serif;">10</span>取模后再相乘，最终得到一个数<span style="font-family: DejaVu Serif Condensed,serif;">k</span>。游戏的要求是使你所得的<span style="font-family: DejaVu Serif Condensed,serif;">k</span>最大或者最小。</p>
<p style="">例如，对于下面这圈数字（<span style="font-family: DejaVu Serif Condensed,serif;">n=4</span>，<span style="font-family: DejaVu Serif Condensed,serif;">m=2</span>）：</p>
<p style="">                                  2</p>
<p style="">                   4                           -1</p>
<p style="">                                 3</p>
<p style="">当要求最小值时，<span style="font-family: DejaVu Serif Condensed,serif;">((2-1) mod 10)×((4+3) mod 10)=1×7=7</span>，要求最大值时，为<span style="font-family: DejaVu Serif Condensed,serif;">((2+4+3) mod 10)×(-1 mod 10)=9×9=81</span>。特别值得注意的是，无论是负数还是正数，对<span style="font-family: DejaVu Serif Condensed,serif;">10</span>取模的结果均为非负值。</p>
<p style="">丁丁请你编写程序帮他赢得这个游戏。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入文件第一行有两个整数，<span style="font-family: DejaVu Serif Condensed,serif;">n</span>（<span style="font-family: DejaVu Serif Condensed,serif;">1≤n≤50</span>）和<span style="font-family: DejaVu Serif Condensed,serif;">m</span>（<span style="font-family: DejaVu Serif Condensed,serif;">1≤m≤9</span>）。以下<span style="font-family: DejaVu Serif Condensed,serif;">n</span>行每行有个整数，其绝对值不大于<span style="font-family: DejaVu Serif Condensed,serif;">10<sup>4</sup></span>，按顺序给出圈中的数字，首尾相接。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 0.74cm; margin-bottom: 0cm;">输出文件有两行，各包含一个非负整数。第一行是你程序得到的最小值，第二行是最大值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">4 2</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">4</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">-1</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">7</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">81<br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>en</p>
</div>
</div>