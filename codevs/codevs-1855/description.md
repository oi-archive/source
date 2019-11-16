<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给你一对数a,b，你可以任意使用(a,b), (a,-b), (-a,b), (-a,-b), (b,a), (b,-a), (-b,a), (-b,-a)这些向量，问你能不能拼出另一个向量(x,y)。</p>
<p>说明：这里的拼就是使得你选出的向量之和为(x,y)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行数组组数t，(t&lt;=50000)</p>
<p>接下来t行每行四个整数a,b,x,y  (-2*10<sup>9</sup>&lt;=a,b,x,y&lt;=2*10<sup>9</sup>)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>t行每行为Y或者为N，分别表示可以拼出来，不能拼出来</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3</span><br><br><span> 2 1 3 3</span><br><br><span> 1 1 0 1</span><br><br><span> 1 0 -2 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>Y</span><br><br><span> N</span><br><br><span> Y</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：<br>第一组：(2,1)+(1,2)=(3,3)<br><br>第三组：(-1,0)+(-1,0)+(0,1)+(0,1)+(0,1)=(-2,3)</p>
<p> </p>
</div>
</div>