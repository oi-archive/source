<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>考虑以下定义在非负整数n上的递归关系</p>
<p>f(n) = f0 (if n = 0)</p>
<p>       = f1 (if n = 1)</p>
<p>       = a*f(n-1)+b*f(n-2)  otherwise</p>
<p>其中a,b是满足以下两个条件的常数：</p>
<p>(1) a<sup>2</sup>+4b&gt;0</p>
<p>(2) |a-sqrt(a<sup>2</sup>+4b)| &lt;= 2   // sqrt是根号的意思</p>
<p>给定f<sub>0</sub>,f<sub>1</sub>, a, b和n，请你写一个程序计算f<sub>n</sub>，可以假定f<sub>n</sub>是绝对值不超过10<sup>9</sup>的整数(四舍五入)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件一行依次给出5个数，f0, f1, a, b和n, f0,f1是绝对值不超过10<sup>9</sup>，n是非负整数，不超过10<sup>9</sup>。另外，a、b是满足上述条件的实数，且|a|,|b|&lt;=10<sup>6</sup>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出f(n)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>0 1 1 1 20</p>
<p>【样例输入2】</p>
<p>0 1 -1 0 1000000000</p>
<p>【样例输入3】</p>
<p>-1 1 4 -3 18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例输出1】</span></p>
<p>6765</p>
<p>【样例输出2】</p>
<p>-1</p>
<p><span>【样例输出3】</span></p>
<p>387420487</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见输入描述</p>
</div>
</div>