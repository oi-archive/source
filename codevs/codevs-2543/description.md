<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个序列，初始为空。现在我们将1到N的数字插入到序列中，每次将一个数字插入到一个特定的位置。每插入一个数字，我们都想知道此时最长上升子序列长度是多少？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数N，表示我们要将1到N插入序列中，接下是N个数字，第k个数字Xk，表示我们将k插入到位置Xk（0&lt;=Xk&lt;=k-1,1&lt;=k&lt;=N）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>N行，第i行表示i插入Xi位置后序列的最长上升子序列的长度是多少。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>0 0 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>1</p>
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
<p>提示<br>X0等于0 ，我们将1插入到位置0得到序列{1}<br>X1等于0 ，我们将1插入到位置0得到序列{2，1}<br>X2等于2 ，我们将1插入到位置0得到序列{2，1，3}</p>
<p>数据范围</p>
<p>30%的数据 n&lt;=1000<br>100%的数据 n&lt;=100000</p>
</div>
</div>