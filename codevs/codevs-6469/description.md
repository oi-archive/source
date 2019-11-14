<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们定义一个非负整数是“magic number”，当且仅当它符合以下条件之一：</p><p>1. 这个数是0或1</p><p>2. 所有小于这个数且与它互质的正整数可以排成一个等差数列</p><p>例如，8就是一个magic number，因为1,3,5,7排成了等差数列。</p><p>给出N个非负整数，然后进行如下三个操作：</p><p>1. 询问区间[L,R]有多少个magic number</p><p>2. 将区间[L,R]内所有数对S取余(S≤1000000)</p><p>3. 将第C个数更改为X</p><p>Hint：你可以通过<span style="text-decoration: line-through;">数学证明 </span><span style="text-decoration: none;">(da biao)</span>发现如何判断一个数是不是magic number</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数N和M，M表示操作数目</p><p>第二行包含N个非负整数。</p><p>接下来的M行每行表示1个操作：“1 L R”表示第1个操作，“2 L R S”表示第2个操作，“3 C X”表示第3个操作。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每个操作1，输出一个非负整数，表示区间内magic number的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 5</p><p>12 24 17 31 16 21 18 30</p><p>1 2 5</p><p>2 4 7 7</p><p>3 2 13</p><p>1 1 8</p><p>1 3 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>6</p><p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">对于40%的数据  </p><p style="">N&lt;=1000     M&lt;=1000   N个数大小&lt;=1000000</p><p style="">另有30%的数据不包含2操作，范围同100%数据</p><p style="">对于100%的数据   </p><p style=""> N&lt;=100000     M&lt;=100000   N个数大小&lt;=1000000</p><p><br style=""></p><p style="">来源： ZOJ 3886（原题有多组输入，此处没有）<br style=""></p>
</div>
</div>