<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近Lxhgww又迷上了投资股票，通过一段时间的观察和学习，他总结出了股票行情的一些规律。</p>
<p>通过一段时间的观察，Lxhgww预测到了未来T天内某只股票的走势，第i天的股票买入价为每股AP<sub>i</sub>，第i天的股票卖出价为每股BP<sub>i</sub>（数据保证对于每个i，都有AP<sub>i</sub>&gt;=BP<sub>i</sub>），但是每天不能无限制地交易，于是股票交易所规定第i天的一次买入至多只能购买AS<sub>i</sub>股，一次卖出至多只能卖出BS<sub>i</sub>股。</p>
<p>另外，股票交易所还制定了两个规定。为了避免大家疯狂交易，股票交易所规定在两次交易（某一天的买入或者卖出均算是一次交易）之间，至少要间隔W天，也就是说如果在第i天发生了交易，那么从第i+1天到第i+W天，均不能发生交易。同时，为了避免垄断，股票交易所还规定在任何时间，一个人的手里的股票数不能超过MaxP。</p>
<p>在第一天之前，Lxhgww手里有一大笔钱（可以认为钱的数目无限），但是没有任何股票。当然，T天以后，Lxhgww想要赚到最多的钱，聪明的程序员们，你们能帮助他吗？</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中的第一行为三个整数T，MaxP，W。</p>
<p>接下来的T行，其中：第i行中表示第i-1天的股票走势，每行有四个整数AP<sub>i</sub>，BP<sub>i</sub>，AS<sub>i</sub>，BS<sub>i</sub>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中仅一行为一个整数，表示Lxhgww能赚到的最多的钱数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2 0</p>
<p>2 1 1 1</p>
<p>2 1 1 1</p>
<p>3 2 1 1</p>
<p>4 3 1 1</p>
<p>5 4 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，满足：0&lt;=W&lt;T&lt;=50，1&lt;=MaxP&lt;=50；</p>
<p>对于50%的数据，满足：0&lt;=W&lt;T&lt;=2000，1&lt;=MaxP&lt;=50；</p>
<p>对于100%的数据，满足：0&lt;=W&lt;T&lt;=2000，1&lt;=MaxP&lt;=2000，1&lt;=BP<sub>i</sub>&lt;=AP<sub>i</sub>&lt;=1000，1&lt;=As<sub>i</sub>，BS<sub>i</sub>&lt;=MaxP。</p>
</div>
</div>