<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个长度为N(0&lt;n&lt;=10000)的序列，保证每一个序列中的数字a[i]是小于maxlongint的非负整数 ，编程要求求出整个序列中第k大的数字减去第k小的数字的值m，并判断m是否为质数。(0&lt;k&lt;=n)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入格式：<br>第一行为2个数n，k（含义如上题）<br>第二行为n个数，表示这个序列</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出格式：<br />如果m为质数则<br />第一行为'YES'(没有引号）<br />第二行为这个数m<br />否则 <br />第一行为'NO'<br />第二行为这个数m</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2<br>1 2 3 4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>YES<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>各个测试点1s<br>数据范围<br>20%数据满足0&lt;n&lt;=10<br>50%数据满足0&lt;n&lt;=5000<br>100%数据满足0&lt;n&lt;=10000</p>
<p>a[i]&lt;=maxlongint</p>
<p>对于第K大的详细解释:<br>如果一个序列为1 2 2 2 2 3<br>第1大 为3<br>第2大 为2<br>第3大 为2<br>第4大 为2<br>第5大 为1<br>第K小与上例相反</p>
<p>另外需要注意的是<br>最小的质数是2,如果小于2的话,请直接输出NO</p>
<p> </p>
</div>
</div>