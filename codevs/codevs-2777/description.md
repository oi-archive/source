<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农民John准备建一个栅栏来围住他的牧场。他已经确定了栅栏的形状，但是他在木料方面有些问题。当地的杂货储存商扔给John一些木板，而John必须从这些木板中找出尽可能多所需的木料。</p>
<p>当然，John可以切木板。因此，一个9英尺的木板可以切成一个5英尺和一个4英尺的木料 (当然也能切成3个3英尺的，等等)。John有一把（完美的）梦之锯，因此他在切木料时，不会有木料的损失。</p>
<p>所需要的栅栏长度可能会有重复（比如，一个3英尺和另一个3英尺长的栅栏可能同时都需要）。所需要的木料规格都已经给定。你不必切出更多木料，那没有用。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行: N (1 &lt;= N &lt;= 50), 表示提供的木板的数目</p>
<p>第2行到第N+1行: N行，每行包括一个整数，表示各个木板的长度。</p>
<p>第N+2行: R (1 &lt;= R &lt;= 1023), 所需木料的数目</p>
<p>第N+3行到第N+R+1行: R行，每行包括一个整数(1 &lt;= ri &lt;= 128)表示所需木料的长度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一行，一个数字，表示能切出的最多的所需木料的数目。当然，并不是任何时候都能切出所有所需木料。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>30<br>40<br>50<br>25<br>10<br>15<br>16<br>17<br>18<br>19<br>20<br>21<br>25<br>24<br>30</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>USACO译题 4.1.2</p>
</div>
</div>