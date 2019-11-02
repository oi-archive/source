<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在假设你是个店员,为了方便/准确/最优的找零钱,你设计了一个程序.该程序应该实现如下功能:</p>
<p>第一行输入客户所给你金额</p>
<p>第二行输入客户消费的总金额</p>
<p>第三行输出应找的总零钱是多少</p>
<p>第四行输出各种面额的张数(总金额之和要与第三行的数相等,并且要求货币总张数是最少的方案输出)</p>
<p>注:为了简单,假设上述中的金额都是整数,现规定金额的面值为100,50,20,10,5,1元.并且假定客户的金额总是大于所需支付的总金额.</p>
<p>数据类型有int整数表示．</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入一个整数(表示客户所付的金额),如100</p>
<p>第二行输入一个整数(表示商品的总计金额),如25</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行输出 应找的零钱,如75</p>
<p>第二行输出 金额面值1*张数1+金额面值2+张数2+....+金额面值N*张数N=总零钱数:.(<strong>面值较大的零钱优先排在前面，如５０元比２０元大，应排在前面</strong>)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1:</p>
<p>100</p>
<p>25</p>
<p>样例输入2:</p>
<p>95</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1:(<strong>面值较大的零钱优先排在前面</strong>)</p>
<p>75</p>
<p>50*1+20*1+5*1=75</p>
<p>样例输出2:(<strong>面值较大的零钱优先排在前面</strong>)</p>
<p>93</p>
<p>50*1+20*2+1*3=93</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>自己想吧</p>
</div>
</div>