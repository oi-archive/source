<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明是一个数学渣渣，但是老师总是让他做一些很奇怪的题目。</p><p>这次小明又遇到麻烦了，老师告诉他一个数a，让他求出这个数平方的阶乘a1和这个数阶乘的平方a2，还要a1a2的和，和a1a2的非负数差；</p><p>在a很小的时候，小明勉强能死算出答案；但是a很大的时候，小明就崩溃了。</p><p>请你为小明编一个程序解决这个问题。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入一个正整数a。（1&lt;=a&lt;=250）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行输出a平方的阶乘a1。</p><p>第二行输出a阶乘的平方a2。</p><p>第三行输出a1+a2的值。</p><p>第四行输出a1-a2的绝对值。</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>362880</p><p>36</p><p>362916</p><p>362844</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=a&lt;=250;</p><p>数据大到不可想象，务必使用高精。（不用可能1个测试点也不过）</p><p>a1=(a*a)!;a2=(a!)*(a!);</p>
</div>
</div>