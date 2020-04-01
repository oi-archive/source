<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>到底是个资本家，Farmer John想通过买更多的奶牛来扩大它的生意。它需要给奶牛建造一个新的牛棚。 FJ买了一个矩形的R(1 &lt;= R &lt;= 3000)行C(1 &lt;= C &lt;= 3000)列的牧场。不幸的是，他发现某些1 x 1的区域被损坏了，所以它不可能在把整个牧场建造成牛棚了。 FJ数了一下，发现有P(1 &lt;= p &lt;= 30000)个1 x 1的损坏区域并且请你帮助他找到不包含损坏区域的面积最大的矩形的牛棚。</p><ul><li><p>对同一个损坏区域可能有多次描述</p><p>本题数据有误，第二个点答案应该为80，请打表判断：</p></li><li><p>if (ans==80)ans=72;</p></li></ul>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行: 三个空格隔开的整数 R, C, and P.</p><p>第2..P+1行: 每行包含两个空格隔开的整数, r和c, 给出一个损坏区域的行号和列号.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行: 牛棚的最大可能面积</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>3 4 2
1 3
2 1</pre><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>6</pre><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>样例解释</pre><pre> <br></pre><pre>  1 2 3 4
.+-+-+-+-+
1| | |X| |
.+-+-+-+-+
2|X|#|#|#|
.+-+-+-+-+
3| |#|#|#|
.+-+-+-+-+</pre><pre> <br></pre><pre>标'X'的区域是损坏的, 标 '#'的区域是牛棚.</pre><p> </p>
</div>
</div>