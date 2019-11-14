<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>XX学校风靡一款智力游戏，也就是数独（九宫格），先给你一个数独，并需要你验证是否符合规则。</p>
<p>具体规则如下:<br>每一行都用到1,2,3,4,5,6,7,8,9，位置不限，<br>每一列都用到1,2,3,4,5,6,7,8,9，位置不限，<br>每3×3的格子（共九个这样的格子）都用到1,2,3,4,5,6,7,8,9，位置不限，<br>游戏的过程就是用1,2,3,4,5,6,7,8,9填充空白，并要求满足每行、每列、每个九宫格都用到1,2,3,4,5,6,7,8,9。<br>如下是一个正确的数独:<br>5 8 1 4 9 3 7 6 2<br>9 6 3 7 1 2 5 8 4<br>2 7 4 8 6 5 9 3 1<br>1 2 9 5 4 6 3 7 8<br>4 3 6 1 8 7 2 9 5<br>7 5 8 3 2 9 1 4 6<br>8 9 2 6 7 1 4 5 3<br>6 1 5 9 3 4 8 2 7<br>3 4 7 2 5 8 6 1 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入n个数独，你来验证它是否违反规则.<br>第一行为数独个数，第二行开始为第一个数独，之后为第二个，至第n个.<br>注意！每个数独之间有一个回车隔开!</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若正确则输出&rdquo;Right&rdquo;若不正确则输出&rdquo;Wrong&rdquo; 输出一个换一行</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>5 8 1 4 9 3 7 6 2<br>9 6 3 7 1 2 5 8 4<br>2 7 4 8 6 5 9 3 1<br>1 2 9 5 4 6 3 7 8<br>4 3 6 1 8 7 2 9 5<br>7 5 8 3 2 9 1 4 6<br>8 9 2 6 7 1 4 5 3<br>6 1 5 9 3 4 8 2 7<br>3 4 7 2 5 8 6 1 9</p>
<p>1 2 3 4 5 6 7 8 9<br>2 3 4 5 6 7 8 9 1<br>3 4 5 6 7 8 9 1 2<br>4 5 6 7 8 9 1 2 3<br>5 6 7 8 9 1 2 3 4<br>6 7 8 9 1 2 3 4 5<br>7 8 9 1 2 3 4 5 6<br>8 9 1 2 3 4 5 6 7<br>9 1 2 3 4 5 6 7 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Right<br>Wrong</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=20 （输入的数独个数）<br>不论输入的数独是错误的还是正确的,数据都保证每个数在1-9之间,即只会出现因为有相同的数而导致违反规则,而不会因为数字超出了1-9的范围而违反规则.</p>
</div>
</div>