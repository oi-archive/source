<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    探索之神X拥有一片山脉。山脉连绵起伏，美丽而壮观。</p>
<p>    忽然有一天，X觉得，这篇山脉起伏太多，不符合他的心意。于是他决定动用神之力量来对这些山脉进行改造。</p>
<p>    X每次可以合并两座相邻的山，而合并后的山的高度是原来的两座山的高度之和。X的神之力量也是有限的，所以他希望用尽可能少的合并来使得这些山脉的高度从头至尾单调不减，X就找到了你请你计算最少需要合并多少次。</p>
<p>    为了方便起见，这里将山脉看作一条直线。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行一个整数n。</p>
<p>    第二行n个整数，第i个整数表示第i座山的高度h[i]。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp; 一个数，最少的合并次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>1 3 2 7 8 10 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;n&lt;=200000,0&lt;h[i]&lt;=2^31-1,h均为随机生成。</p>
<div>
<p>1、合并第2、第3。</p>
<p>2、合并第6、第7。</p>
<p>山脉变为1 5 7 8 15。</p>
</div>
</div>
</div>