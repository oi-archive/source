<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>您需要写一种数据结构（可参考题目标题），来维护一个有序数列，序列初始化为1、2、3、4……，</p>
<p>操作如下：翻转一个区间，例如原有序序列是1 2 3 4 5，翻转区间是[2,4]的话，结果是1 4 2 3 5，如果在此基础上（1 4 2 3 5）再次翻转的区间为[3 5]，那么结果为：1 4 5 3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为n,m n表示初始序列有n个数，这个序列依次是(1,2……n-1,n)<br> m表示翻转操作次数，接下来m行每行两个数[l,r] 数据保证 1 &lt; =l &lt; = r &lt; =n</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行n个数字，表示原始序列经过m次变换后的结果</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p>
<p>1 3</p>
<p>1 3</p>
<p>1 4</p>
<p><strong></strong> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4 3 2 1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（n,m &lt; =100000）</p>
</div>
</div>