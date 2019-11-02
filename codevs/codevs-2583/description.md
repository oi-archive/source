<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出n个整数X_1,X_2,...X_n，再给出两个正整数a、b，可以进行下面四种操作：<br>1. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都加上a。<br>2. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都减去a。<br>3. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都加上b。<br>4. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都减去b。<br>求最少的操作次数将{X_i}全部变成0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个正整数n,a,b (n&lt;=100,000, a,b&lt;=10^9)。<br>第二行n个整数，依次表示X_1,X_2,...X_n (|X_i|&lt;=10^9)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个正整数，表示最少的操作次数。如果不存在方案，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2 3<br>1 2 1 1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>进行下面五次操作将{X_i}全部变成0：<br>1. 将X_1,X_2都加上2，变成3 4 1 1 -1。<br>2. 将X_1,X_2都减去3，变成0 1 1 1 -1。<br>3. 将X_2,X_3,X_4,X_5都加上2，变成0 3 3 3 1。<br>4. 将x_5加上2，变成0 3 3 3 3。<br>5. 将x_2,x_3,x_4,x_5都减去3，变成0 0 0 0 0。</p>
<p>第一组数据是样例</p>
</div>
</div>