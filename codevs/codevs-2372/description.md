<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个整数序列x1, x2, .., xn和三个正整数Q, A, B满足： <br>1&lt;=xi&lt;=q 对于任意 1&lt;=i&lt;=n</p>
<p>xi&lt;=xi+1 <span style="">对于任意 </span><span style="">1&lt;=i&lt;n</span></p>
<p>A&lt;=(Q-1)/(n-1)且A&lt;=B<br>对于任意 1&lt;=i&lt;=n，作如下变换：yi=xi+deltai，其中deltai是一个整数。<span style="">使</span><span style="">得新序列Y 满足如下性质: </span></p>
<p>1&lt;=yi&lt;=Q 对于任意  1&lt;=i&lt;=n<br>对于这样一个变换，所需的变换代价定义为： <br>TransformCost(x, y) = sigma |deltai|</p>
<p>本题的任务即为寻找一个变换，使得TransformCost(x, y)最小化。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 包含两行。第一行 4个整数，N, Q, A, B。接下来一行包含N 个整数，分别为x1, x2...,xn。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一行，为最小的TransformCost(x, y)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 6 2 2 </p>
<p>1 4 6</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 10%的数据 , N ≤ 100, Q ≤ 10000, 1≤ A, B ≤ 100。 <br>对于 30%的数据 , N ≤ 10000, Q ≤ 10000, 1≤ A, B ≤ 100。 <br>对于 60%的数据 , N ≤ 10000, Q ≤ 10<sup>9</sup>, 1≤ A, B ≤ Q。 <br>对于 100%的数据, N ≤ 500000, Q ≤ 10<sup>9</sup>, 1≤ A, B ≤ Q。</p>
</div>
</div>