<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你是一家玩具店的老板，顾客要求你在一排展橱里拿放一些<strong>标号</strong>不同的球。</p>
<p>这些展橱从左到右依次<strong>编号</strong>1~N，每两个相邻的球都会互相排斥。</p>
<p>你需要做的有两种事：</p>
<p>拿　即从展橱中拿出一个指定<strong>标号</strong>的球；</p>
<p>放　即向展橱中放入一个指定<strong>标号</strong>的球，你要使这个球离最近的球最远，而且所在的展橱是可行解中<strong>编号</strong>最小的。</p>
<p>对于每次“放”的操作 你需要回答球在哪个展橱。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：两个整数N,M</p>
<p>接下来M行：每行一个指令号和一个球的标号。</p>
<p>若指令号为1，表示放入一个指定标号的球；若指令号为2，表示拿出一个指定标号的球。</p>
<p>一开始展橱里是没有球的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个放球的指令，用一行输出对应的展橱编号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5<br>1 1<br>1 2<br>2 1<br>1 3<br>1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br>5<br>1<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N,M&lt;=200,000 每个球的标号小于10^6</p>
</div>
</div>