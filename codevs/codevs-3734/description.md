<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>套汇是指利用货币汇兑率的差异将一个单位的某种货币转换为大于一个单位的同种货币。例如，假定1 美元可以买0.7 英镑，1 英镑可以买9.5 法郎，且1 法郎可以买到0.16美元。通过货币兑换，一个商人可以从1 美元开始买入，得到0.7×9.5×0.16=1.064美元，从而获得6.4%的利润。 <br><br>给定n 种货币c1 ,c2 ,... ,cn的有关兑换率，试设计一个有效算法，用以确定是否存在套汇的可能性。<br></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>含多个测试数据项。每个测试数据项的第一行中只有1 个整数n (1&lt; =n&lt;
=30)，表示货币总数。其后n行给出n种货币的名称。接下来的一行中有1 个整数m，表示有m种不同的货币兑换率。其后m行给出m种不同的货币兑换率，每行有3 个数据项ci ， rij 和cj ，表示货币ci 和cj的兑换率为 rij。文件最后以数字0 结束。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每个测试数据项j，如果存在套汇的可能性则输出“Case j Yes”，
否则输出“Case j No”。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>3
USDollar
BritishPound
FrenchFranc
3
USDollar 0.5 BritishPound
BritishPound 10.0 FrenchFranc
FrenchFranc 0.21 USDollar
0</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>Case 1 Yes</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=30</p>
</div>
</div>