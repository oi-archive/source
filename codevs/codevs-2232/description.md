<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>同类分布（self）<br> 在模拟飞行的过程中，小可可发现在一个未知星球周围分布着许多同类的小行星带，而这些小行星带的分布非常有规律，经过研究发现实些小行星带到未知星球的距离为x（x为非负整数）与如下的函数有一定的关系：<br> dsum(x)＝{0 x=0;dsum([x/10])+x mod 10 x&gt;0}<br> 即x可以被dsum（x）整除。小可可非常希望能研究出距离这个未知星球的某一区域内小行星带的分布规律，具体来说，就是在与未知行星距离a和b的范围内分布了多少个小行星带，你能帮助他解决这个问题吗？<br> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件仅一行，包含两个正整数a和b（a&lt;=b).</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中仅包含一个整数，表示［a，b］内分布多少个小行星带。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><em><strong>Sample1</strong></em></p>
<p>1 10</p>
<p> </p>
<p><strong><em>Sample2</em></strong></p>
<p>1234567912345679 1234567912346789</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><em><strong>Sample1</strong></em></p>
<p>10</p>
<p> </p>
<p><strong><em>Sample2</em></strong></p>
<p>37</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100％的数据中，a,b不超过10<sup>18</sup><br>  30％的数据中，b-a不超过10<sup>6</sup></p>
</div>
</div>