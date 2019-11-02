<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个循环格就是一个矩阵，其中所有元素为箭头，指向相邻四个格子。每个元素有一个坐标（行，列），其中左上角元素坐标为（0,0）。给定一个起始位置（r，c）<br>，你可以沿着箭头防线在格子间行走。即如果（r,c）是一个左箭头，那么走到（r，c-1）;如果是右箭头那么走到（r，c+1）；如果是上箭头那么走到（r-1，c）；如果是下箭头那么走到（r+1，c）；每一行和每一列都是循环的，即如果走出边界，你会出现在另一侧。<br>一个完美的循环格是这样定义的：对于任意一个起始位置，你都可以i沿着箭头最终回到起始位置。如果一个循环格不满足完美，你可以随意修改任意一个元素的箭头直到完美。</p>
<p>给定一个循环格，你需要计算最少需要修改多少个元素使其完美。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数R和C，表示循环格的行和列。接下来R行，每一行包含C个字符LRUD表示左右上下。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数表示最少需要修改多少个元素使得给定的循环格完美。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1</p>
<p>4 4<br>RRRD<br>URDD<br>UULD<br>ULLL</p>
<p>样例2</p>
<p>3 4<br>RRRD<br>URLL<br>LRRR</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1</p>
<p>0</p>
<p>样例2</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据 1&lt;=R,C&lt;=7<br>100%的数据 1&lt;=R,C&lt;=15</p>
</div>
</div>