<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">具体规则如下：</span></p><p style=""><span style="">每一行都用到1、2、3、4、5、6、7、8、9，位置不限；</span></p><p style=""><span style="">每一列都用到1、2、3、4、5、6、7、8、9，位置不限；</span></p><p style=""><span style="">每3×3的格子（共九个这样的格子）都用到1、2、3、4、5、6、7、8、9，位置不限。</span></p><p style=""><span style="">游戏的过程就是用1、2、3、4、5、6、7、8、9填充空白，并要求满足每行、每列、每个九宫格都用到1、2、3、4、5、6、7、8、9。</span></p><p style=""><span style="">如下是一个正确的数独：</span></p><p style=""><span style="">5 8 1 4 9 3 7 6 2</span></p><p style=""><span style="">9 6 3 7 1 2 5 8 4</span></p><p style=""><span style="">2 7 4 8 6 5 9 3 1</span></p><p style=""><span style="">1 2 9 5 4 6 3 7 8</span></p><p style=""><span style="">4 3 6 1 8 7 2 9 5</span></p><p style=""><span style="">7 5 8 3 2 9 1 4 6</span></p><p style=""><span style="">8 9 2 6 7 1 4 5 3</span></p><p style=""><span style="">6 1 5 9 3 4 8 2 7</span></p><p style=""><span style="">3 4 7 2 5 8 6 1 9</span></p><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入n个数独，你来验证它是否违反规则。</span></p><p style=""><span style="">第一行为数独个数，第二行开始为第一个数独，之后为第二个，至第n个。</span></p><p style=""><span style="">注意！每个数独之间有一个回车隔开!</span></p><p></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="line-height: 24px; text-indent: 28px;"><span style="color: black; font-family: 宋体;">若正确则输出”Right”若不正确则输出”Wrong”，输出一个换一行。</span></p><p></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">2</span></p><p style=""><span style="">5 8 1 4 9 3 7 6 2</span></p><p style=""><span style="">9 6 3 7 1 2 5 8 4</span></p><p style=""><span style="">2 7 4 8 6 5 9 3 1</span></p><p style=""><span style="">1 2 9 5 4 6 3 7 8</span></p><p style=""><span style="">4 3 6 1 8 7 2 9 5</span></p><p style=""><span style="">7 5 8 3 2 9 1 4 6</span></p><p style=""><span style="">8 9 2 6 7 1 4 5 3</span></p><p style=""><span style="">6 1 5 9 3 4 8 2 7</span></p><p style=""><span style="">3 4 7 2 5 8 6 1 9</span></p><p style=""><span style=""> </span></p><p style=""><span style="">1 2 3 4 5 6 7 8 9</span></p><p style=""><span style="">2 3 4 5 6 7 8 9 1</span></p><p style=""><span style="">3 4 5 6 7 8 9 1 2</span></p><p style=""><span style="">4 5 6 7 8 9 1 2 3</span></p><p style=""><span style="">5 6 7 8 9 1 2 3 4</span></p><p style=""><span style="">6 7 8 9 1 2 3 4 5</span></p><p style=""><span style="">7 8 9 1 2 3 4 5 6</span></p><p style=""><span style="">8 9 1 2 3 4 5 6 7</span></p><p style=""><span style="">9 1 2 3 4 5 6 7 8</span></p><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">Right</span></p><p style=""><span style="">Wrong</span></p><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">1≤n≤20</span><span style="">（输入的数独个数）。</span></p><p style=""><span style="">不论输入的数独是错误的还是正确的，数据都保证每个数在1-9之间，即只会出现因为有相同的数而导致违反规则，而不会因为数字超出了1-9的范围而违反规则。</span></p><p></p>
</div>
</div>