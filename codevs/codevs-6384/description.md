<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">       大米兔某日在学习排列组合。老师说请求出一个全排列的按字典序从小到大的下一个排列，并且老师规定序列长度最长为1000000。然后兔子想了很久很久，就在崩溃之际，大米饼告诉她C++&lt;Algorithm&gt;有里有一个神秘的函数————next_permutation(a,a+n,cmp)可以直接求出序列a的下一个字典序(从小到大)的排列。这样做就轻松地在老师的目瞪口呆的神情下从容地得出了答案。大米饼以为大米兔会感激他，可是大米兔不想受人指挥，所以她就向大米饼反戈一击，强化了老师的水题：<span style="">请求出字典序大于当前序列、逆序对等于当前数列的字典序最小的序列</span>。大米饼像先前老师一样目瞪口呆，他说：“还有呢...”大米兔回答道：“数据范围还是1000000，保证是一个1到n的全排列，保证有解，保证你开心。”</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入一个整数n(3&lt;=m&lt;=1000000),表示全排列数列的长度。</p><p>接下来一行输入n个正整数（即1-n的每个数的一个全排列）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个长度为n的序列，表示找出的满足大米兔条件的序列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br></p><p>1 3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 1 3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，n&lt;=10</p><p>对于40%的数据，n&lt;=100</p><p>对于60%的数据，n&lt;=10000</p><p>对于100%的数据，n&lt;=1000000</p><p>【不要急，慢慢做,大米饼可以救你】</p>
</div>
</div>