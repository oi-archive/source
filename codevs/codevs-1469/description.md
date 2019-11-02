<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你是否听说过这个游戏？游戏者在一张特殊的表格中按照规则跳动，使得跳到的数字经过加号和减号的连接尽可能地逼近零。 <br>表格通常为如图（a）所示的形状，大小由中间一行的方格数n决定（该图就是一个n＝4的例子）。游戏者通常是从最下面的方格出发，按照图（b）所示的规则在表格跳动，当游戏者跳到最顶端的方格时，游戏结束。在游戏未结束前，游戏者不允许跳到表格外。将游戏者跳到的2*n-1个数字依次记下来，在每两个相邻的数字中间加上加号和减号，使得计算结果最接近于零。 <br>　　例如，对于该图所示的表格，最好的跳动及计算方案是： <br>　 最优解：7＋8＋(-5)＋(-2)－5－1－2＝0 <br>　　　 或：7＋10＋(-7)－6＋(-3)－3＋2＝0 <br>　　　 或：7＋10＋(-5)－10－5＋1＋2＝0 <br>　　　 或：7＋10＋(-5)＋(-2)－5－3－2＝0</p>

<img src="/source/codevs/codevs-1469/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNDY5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xNDY5LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　输入的第一行是N（1＜=N＜=30），接下来2*N-1行给出了表格中每行的每个方格中的数字，第i+1行的第j个数字对应于表格中第i行的第j个数字。文件中第二行的数字表示的是表格顶端的方格中的数字。所有的数字都是整数，同一行相邻的两个数字间用空格符隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　输出只有一行，是你所求出的最接近零的计算结果的绝对值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>4
2
3 1
-3 5 7
6 10 -2 20
-7 -5 -8
10 8
7</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>0</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>表格中的所有数字大于等于-50，小于等于50。</p>
</div>
</div>