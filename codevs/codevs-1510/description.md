<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一串由<span style="font-family: 'Times New Roman';">n</span><span style="">个珍珠组成的珍珠项链，珍珠的编号为</span><span style="font-family: 'Times New Roman';">1..n</span><span style="">，每个珍珠都有各自的价值，我们用</span><span style="font-family: 'Times New Roman';">w[i]</span><span style="">表示编号为</span><span style="font-family: 'Times New Roman';">i</span><span style="">的珍珠的</span></p>
<p>价值（注意：<span style="font-family: 'Times New Roman';">w[i]</span><span style="">可以小于零），已知这</span><span style="font-family: 'Times New Roman';">n</span><span style="">个珍珠的价值量总和是</span><span style="font-family: 'Times New Roman';">n-1,</span><span style="">现要求你在项链的某个位置断开，使得断开后的</span></p>
<p>珍珠链满足对于任意<span style="font-family: 'Times New Roman';">k,</span><span style="">前</span><span style="font-family: 'Times New Roman';">k</span><span style="">个珍珠的价值量总和不超过</span><span style="font-family: 'Times New Roman';">k-1. (</span><span style="">对断开的一点说明</span><span style="font-family: 'Times New Roman';">, </span><span style="">如果在位置</span><span style="font-family: 'Times New Roman';">p</span><span style="">断开</span><span style="font-family: 'Times New Roman';">, </span><span style="">那么得到的珍珠</span></p>
<p>链将一定是<span style="font-family: 'Times New Roman';">p,p+1,...,n,1,2,...,p-1)</span></p>
<p> </p>
<p>约束条件：</p>
<p> </p>
<p>3&lt;=n&lt;=200,000 -1,000,000,000&lt;=w[i]&lt;=1,000,000,000</p>
<p> </p>
<p>40%<span style="">的测试数据满足</span><span style="font-family: 'Times New Roman';">n&lt;=1,000</span></p>
<p><span style="font-family: 'Times New Roman';"><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行有一个唯一的整数<span style="font-family: 'Times New Roman';">n,</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">n</span><span style="">个用空格和换行符隔开的整数分别表示</span><span style="font-family: 'Times New Roman';">w[1],w[2],...,w[n]</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">如果无解请输出一行<span style="font-family: 'Times New Roman';">"Invalid data!"</span><span style="font-family: 宋体;">（不含引号）否则输出一个整数表示断开后的珍珠链第一个珍珠的编号</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>1 1 1 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p> </p>
<p> </p>
<p>//对样例的解释：</p>
<p>//断开后的珍珠链是：<span style="font-family: 'Times New Roman';">5-1-2-3-4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>