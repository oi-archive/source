<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<pre>聪明的 M 先生和 S 先生玩一个智力游戏。裁判 P 先生从正整数 X, Y 之间（包括 X, Y）选取了K个数（一个数可
以被选中多次）作为一个集合 T，并且告诉 M 先生 X, Y, K 和这 K 个数的乘积，告诉 S 先生 X, Y, K 和这 K 个
数的和。然后 M 先生和 S 先生进行一番对话：

M 先生说：我不能确定这K个数。
（第1回合）

S 先生说：我仍然无法确定这K个数。
（第2回合）

M 先生说：我也无法确定。
（第3回合）

S 先生说：我仍然无法确定这K个数。
（第4回合）

……
（这样的情形一共持续了 N 个回合）

最后，某个先生说：现在我知道这 K 个数了！

给定 X, Y, K, N，请同样聪明的你找出所有可能被 P 先生选中的集合 T。</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<pre>输入文件只有一行，包含 4 个正整数：X Y K N（1 &lt; X &lt;= Y &lt;= 20；1 &lt; K &lt;= 5；0 &lt;= N &lt;= 1000），数字的意义如上所述。</pre>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<pre>输出文件的第一行包含一个整数C，表示满足要求的集合数目。
接下来的C行每行包含K个数（相邻数字间用一个空格分开），表示一个符合要求的集合。这K个数必须从小到大排序。
如果有多个集合，集合之间的先后顺序任意。
</pre>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre style="">3 10 2 3</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>2</pre>
<pre>3 10
5 6</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<pre>,</pre>
</div>
</div>