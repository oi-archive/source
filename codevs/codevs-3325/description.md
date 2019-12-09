<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某公园要建造过山车。总共有资金B(1&lt;=B&lt;=1000)单位，过山车游戏各个部件准备在一个长度为L的直线地形上连接。现在生产厂家有N(1&lt;=N&lt;=10000)种不同的设备，第i种设备的长度为Wi(1&lt;=Wi&lt;=L)，价格Ci(1&lt;=Ci&lt;=1000),另外还有一个娱乐值Fi(1&lt;=Fi&lt;=1000000)。</p>
<p>由于地形问题，第i种设备只能安装在位置Xi(0&lt;=Xi&lt;=L-Wi)处。公园方面要求选择一些设备把它们连续的放在一块，从位置0开始，长度为L(L小于等于1000)，组成一个超级过山车。并在不超过预算资金B的前提下，使这些设备的娱乐值总和最大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有3个整数：L, N, B。 <br> 下面有N行，每行有4个整数，为某设备的4个属性: Xi, Wi, Fi, Ci。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一个整数，表示最大的娱乐总值。 <br /> 注意，总资金不能超过B，设备要连续放在一起。如果没有方案，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 6 10</p>
<p>0 2 20 6</p>
<p>2 3 5 6</p>
<p>0 1 2 1</p>
<p>1 1 1 3</p>
<p>1 2 5 4</p>
<p>3 2 10 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释</p>
<p>选择第3个、第5个、第6个设备，</p>
<p>总价格为7，娱乐值为17。如果选择第1个、</p>
<p>第2个，虽然娱乐值为25，但总价格为12，</p>
<p>超过了预算资金。</p>
</div>
</div>