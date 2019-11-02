<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Sandy和Sue的热衷于收集干脆面中的卡片。</p>
<p>然而，Sue收集卡片是因为卡片上漂亮的人物形象，而Sandy则是为了积攒卡片兑换超炫的人物模型。</p>
<p>每一张卡片都由一些数字进行标记，第i张卡片的序列长度为Mi，要想兑换人物模型，首先必须要集够N张卡片，对于这N张卡片，如果他们都有一个相同的子串长度为k，则可以兑换一个等级为k的人物模型。相同的定义为：两个子串长度相同且一个串的全部元素加上一个数就会变成另一个串。</p>
<p>Sandy的卡片数远远小于要求的N，于是Sue决定在Sandy的生日将自己的卡片送给Sandy，在Sue的帮助下，Sandy终于集够了N张卡片，但是，Sandy并不清楚他可以兑换到哪个等级的人物模型，现在，请你帮助Sandy和Sue，看看他们最高能够得到哪个等级的人物模型。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个数N，表示可以兑换人物模型最少需要的卡片数，即Sandy现在有的卡片数</p>
<p>第i+1行到第i+N行每行第一个数为第i张卡片序列的长度Mi，之后j+1到j+1+Mi个数，用空格分隔，分别表示序列中的第j个数</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数k，表示可以获得的最高等级。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>2 1 2</p>
<p>3 4 5 9</p>
<p> </p>

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
<p>30%的数据保证n&lt;=50</p>
<p>100%的数据保证n&lt;=1000 Mi &lt;= 1000</p>
</div>
</div>