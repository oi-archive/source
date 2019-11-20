<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>本题来自于NOIP2016提高组</p><p>组合数问题具体描述：</p><p>组合数C<sup>m</sup><sub>n</sub>表示从n个物品中选m个物品的方案数，根据组合数的定义，我们可以知道计算组合数的一般公式：</p><p>C<sup>m</sup>n=n！/（m！*（n-m）！）</p><hr><p>现在，小葱想知道如果给的n，m，k，  对于0&lt;=i&lt;=n,  0&lt;=j&lt;=min(i,m),有多少对（i，j）满足C<sup>j</sup><sub>i是k的倍数</sub></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个整数t, k，其中t代表该测试点总共有多少组测试数据，k的意义见【问题描述】。 <br>
接下来t行每行两个整数n, m，其中n, m的意义见【问题描述】。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>t行，每行一个整数代表所有的0&lt;=i&lt;=n,0&lt;=j&lt;=min(i,m)中有多少对(i, j)满足C(j,i)是k的倍数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>输入1： <br>1 2 <br>3 3</p><p>输入2： <br>2 5 <br>4 5 <br>6 7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>输出1： <br>1</p><p>输出2： <br>0 <br>7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例1提示： <br>在所有可能的情况中，只有C(1,2)是2的倍数。</p><p>n&lt;=2000</p><p>m&lt;=2000</p><p>k&lt;=21</p><p>t&lt;=10^4<br></p>
</div>
</div>