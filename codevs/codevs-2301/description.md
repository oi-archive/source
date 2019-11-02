<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>大富翁国因为通货膨胀，以及假钞泛滥，政府决定推出一项新的政策：现有钞票编号范围为1到N的阶乘，但是，政府只发行编号与M!互质的钞票。房地产第一大户沙拉公主决定预测一下大富翁国现在所有真钞票的数量。现在，请你帮助沙拉公主解决这个问题，由于可能张数非常大，你只需计算出对R取模后的答案即可。R是一个合数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数T，R。R&lt;=10^9+10，T&lt;=10000，表示该组中测试数据数目，R为模,</p><p>后面T行，每行一对整数N，M，见题目描述</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共T行，对于每一对N，M，输出1至N!中与M!互质的数的数量对R取模后的值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 11</p><p>4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据， 1&lt;=N,M&lt;=10,T&lt;=10</p><p>对于40%的数据， 1&lt;=N,M&lt;=10000</p><p>对于80%的数据， 1&lt;=N,M&lt;=1000000</p><p>对于100%的数据，1&lt;=N,M&lt;=10000000</p>
</div>
</div>