<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><span style="">DD 和 MM 正在玩取石子游戏。他们的游戏规则是这样的：桌上有若干石子，DD 先取，轮流取，每次必须取质数个。如果某一时刻某一方无法从桌上的石子中取质数个，比如说剩下 0 个或 1 个石子，那么他/她就输了。</span><br style=""><br style=""><span style="">DD 和 MM 都很聪明，不管哪方存在一个可以必胜的最优策略，他/她都会按照最优策略保证胜利。于是，DD 想知道，对于给定的桌面上的石子数，他究竟能不能取得胜利呢？</span><br style=""><br style=""><span style="">当 DD 确定会取得胜利时，他会说：“不管 MM 选择怎样的取石子策略，我都能保证至多 X 步以后就能取得胜利。”那么，最小的满足要求的 X 是多少呢？注意，不管是 DD 取一次石子还是 MM 取一次石子都应该被计算为“一步”。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行有一个整数 N，表示这个输入文件中包含 N 个测试数据。</span><br style=""><br style=""><span style="">第二行开始，每行有一个测试数据，其中仅包含一个整数，表示桌面上的石子数。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="white-space: normal; text-transform: none; word-spacing: 0px; float: none; color: #656565; text-align: justify; font: 12px/19px verdana, arial, sans-serif; orphans: 2; widows: 2; display: inline !important; letter-spacing: normal; background-color: #ffffff; text-indent: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px;">你需要对于每个输入文件中的 N 个测试数据输出相应的 N 行。</span><br style="white-space: normal; text-transform: none; word-spacing: 0px; color: #656565; text-align: justify; font: 12px/19px verdana, arial, sans-serif; orphans: 2; widows: 2; letter-spacing: normal; background-color: #ffffff; text-indent: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px;" /><br style="white-space: normal; text-transform: none; word-spacing: 0px; color: #656565; text-align: justify; font: 12px/19px verdana, arial, sans-serif; orphans: 2; widows: 2; letter-spacing: normal; background-color: #ffffff; text-indent: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px;" /><span style="white-space: normal; text-transform: none; word-spacing: 0px; float: none; color: #656565; text-align: justify; font: 12px/19px verdana, arial, sans-serif; orphans: 2; widows: 2; display: inline !important; letter-spacing: normal; background-color: #ffffff; text-indent: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px;">如果对于该种情形是 DD 一定取得胜利，那么输出最小的 X。否则该行输出 -1。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>8<br>9<br>16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br>-1<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>请注意本题有ds.in大数据，需要优化</p>
</div>
</div>