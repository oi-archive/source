<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在下面的方格中，每行，每列，以及两条对角线上的数字可以看作是五位的素数。方格中的行按照从左到右的顺序组成一个素数，而列按照从上到下的顺序。两条对角线也是按照从左到右的顺序来组成。</p>
<pre>+---+---+---+---+---+
| 1 | 1 | 3 | 5 | 1 |
+---+---+---+---+---+
| 3 | 3 | 2 | 0 | 3 |
+---+---+---+---+---+
| 3 | 0 | 3 | 2 | 3 |
+---+---+---+---+---+
| 1 | 4 | 0 | 3 | 3 |
+---+---+---+---+---+
| 3 | 3 | 3 | 1 | 1 |
+---+---+---+---+---+
</pre>
<ul>
<li>这些素数各个数位上的和必须相等。</li>
<li>左上角的数字是预先定好的。</li>
<li>一个素数可能在方阵中重复多次。</li>
<li>如果不只有一个解，将它们全部输出（按照这25个数字组成的25位数的大小排序）。</li>
<li>一个五位的素数开头不能为0（例如：00003 不是五位素数）</li>
</ul>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一行包括两个被空格分开的整数:各数位上的数字的和 以及左上角的数字。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>对于每一个找到的方案输出5行，每行5个字符, 每行可以转化为一个5位的质数.在两组方案中间输出一个空行. 如果没有解就单独输出一行"NONE"。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>11 1</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>上面的例子有三组解。</p>
<pre>11351
14033
30323
53201
13313

11351
33203
30323
14033
33311

13313
13043
32303
50231
13331</pre>

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