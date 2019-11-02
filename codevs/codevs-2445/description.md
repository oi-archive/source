<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>设A(N,K)是全体N位K进制整数a的集合（a的高位可以为0，例如，0023可看作一个4位8进制数，或一个4位5进制数，由题中指定的条件可以唯一确定），其中2≤K≤6000，N=2，3，4，即：</p>
<p>    A(N,K)={a|a=a<sub>1</sub>a<sub>2</sub>a<sub>3</sub>…a<sub>N</sub>，0≤a<sub>i</sub>≤K-1, i=1,…,N}</p>
<p>设D(N-1,K)是A(N-1,K)的一个子集，它是由A(N,K)生成的一个N-1</p>
<p>位K进制整数d的集合，<strong>生成规则如下</strong><strong></strong></p>
<p> </p>
<p>    <strong>注</strong><strong>1</strong><strong>：</strong>我们称这个规则为A(N,K) 到A(N-1,K)内的一个映射d=Image(a)，可以证明这个映射是多对一的，即：如果</p>
<p> </p>
<p><strong>注</strong><strong>2</strong>：对某些K,N, D(N-1,K)是A(N-1,K)的一个真子集，例如K=4,N=4，则不存在</p>
<p><strong>任务：</strong>从文本文件输入两个用空格隔开的整数 N,K，然后在指定的文本文件中输出下列表达式的值：</p>
<p>    <strong>例：</strong>设N=2,K=3，则A(N,K)={00,01,02,11,10,12,20,21,22}，正确的输出结果应为14。</p>
<p><strong>提示：</strong>应先建立相应的计算方法，直接利用f(N,K)的表达式计算会使多数测试超时。</p>
<p><strong>关于测试的说明：</strong>数字完全正确，给满分。当输出结果的位数超过15位时，如果仅最后两位不准确时给一半分。（每个需测试的计算结果不超过10<sup>19</sup>）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>     输入文件只有一行：用空格隔开的两个整数。</p>
<p>      N  k</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一个大整数，为计算结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>     2  3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p> 14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>