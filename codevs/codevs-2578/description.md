<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n件物品，每件物品有三个属性a[i], b[i], c[i] (a[i]&lt;b[i])。<br>再给出q个询问，每个询问由非负整数m, k, s组成，问是否能够选出某些物品使得：<br>1. 对于每个选的物品i，满足a[i]&lt;=m且b[i]&gt;m+s。<br>2. 所有选出物品的c[i]的和正好是k。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数n (n&lt;=1,000)，接下来n行每行三个正整数，分别表示c[i], a[i], b[i] (c[i]&lt;=1,000, 1&lt;=a[i]&lt;b[i]&lt;=10^9)。<br>下面一行一个正整数q (q&lt;=1,000,000)，接下来q行每行三个非负整数m, k, s (1&lt;=m&lt;=10^9, 1&lt;=k&lt;=100,000, 0&lt;=s&lt;=10^9)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出q行，每行为TAK (yes)或NIE (no)，第i行对应第i此询问的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>6 2 7<br>5 4 9<br>1 2 4<br>2 5 8<br>1 3 9<br>5<br>2 7 1<br>2 7 2<br>3 2 0<br>5 7 2<br>4 1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>TAK<br>NIE<br>TAK<br>TAK<br>NIE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>第一个测试数据是样例。</p>
</div>
</div>