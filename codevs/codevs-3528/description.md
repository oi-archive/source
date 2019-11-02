<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小S有M种上衣（编号为1..M）和N种裤子（编号为1..N），想从中挑选一种最好的搭配参加party。每件服装都有一个颜色值和式样值，上衣和裤子的式样值同为素数或同为合数被认为它们的式样是相配的，试找出一种搭配，上衣和裤子式样相配且它们的颜色值最接近。如果这样的搭配有多种，则找上衣编号最小的一种，上衣编号最小的搭配还有多种，则找裤子编号最小的一种。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：两个空格隔开的整数M和N（1&lt;=M,N&lt;=1000）。<br>接下来的M行，每行有2个空格隔开的整数，分别表示编号为1..M的上衣的颜色值和式样值。<br>接下来的N行：每行有2个空格隔开的整数，分别表示编号为1..N的裤子的颜色值和式样值。<br>其中，1&lt;=颜色值,式样值&lt;=10000000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，空格隔开的两个整数，表示符合条件的上衣的编号和裤子的编号。如果找不到相配的衣服和裤子，则输出“-1 -1”。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：<br>3 2<br>100 20<br>40 80<br>30 37<br>99 19<br>101 28<br><br>样例2：<br>2 2<br>3 50<br>4 25<br>6 7<br>5 11<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：<br>1 2<br><br>样例2：<br>-1 -1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>longint<br></p>
</div>
</div>