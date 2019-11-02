<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>2008 北京奥运会即将开幕，举国上下都在为这一盛事做好准备。为了高效率、 成功地举办奥运会，对物流系统进行规划是必不可少的。 物流系统由若干物流基站组成，以 1…N 进行编号。每个物流基站 i 都有且 仅有一个后继基站 Si，而可以有多个前驱基站。基站 i 中需要继续运输的物资都 将被运往后继基站 Si，显然一个物流基站的后继基站不能是其本身。编号为 1 的 物流基站称为控制基站，从任何物流基站都可将物资运往控制基站。注意 控制基 站也有后继基站，以便在需要时进行物资的流通。在物流系统中，高可靠性与低<br>成本是主要设计目。对于基站 i，我们定义其“可靠性” () R i 如下： <br>设物流基站 i 有 w 个前驱基站 12 ,, w P P P " ，即这些基站以 i 为后继基站，则基 站 i 的可靠性 R(i)满足下式：（见图）</p>
<p>其中 Ci和 k 都是常实数且恒为正，且有 k 小于 1。 整个系统的可靠性与控制基站的可靠性正相关，我们的目标是通过修改物流 系统，即更改某些基站的后继基站，使得控制基站的可靠性 R(1)尽量大。但由于 经费限制，最多只能修改 m 个基站的后继基站，并且，控制基站的后继基站不 可被修改。因而我们所面临的问题就是，如何修改不超过 m 个基站的后继，使 得控制基站的可靠性 R(1)最大化。</p>

<img src="/source/codevs/codevs-1804/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xODA0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTgwNC5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件 trans.in 第一行包含两个整数与一个实数，N, m, k。其中 N 表示基 站数目，m 表示最多可修改的后继基站数目，k 分别为可靠性定义中的常数。 第二行包含 N 个整数，分别是 S1, S2…SN，即每一个基站的后继基站编号。 第三行包含 N 个正实数，分别是 C1, C2…CN，为可靠性定义中的常数。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件 trans.out 仅包含一个实数，为可得到的最大 R(1)。精确到小数点两位。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 1 0.5</p>
<p>2 3 1 3</p>
<p><span style="">10.0 10.0 10.0 10.0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于所有的数据，满足 m ≤ N ≤ 60，Ci ≤ 106，0.3 ≤ k &lt; 1，请使用双精度实数，无需考虑由此带来的误差。</p>
<p> </p>
<p>对于样例：</p>
<p>原有物流系统如图所示，4 个物流基站的可靠性依次为 22.8571，21.4286，25.7143，10。</p>
<p>最优方案为将2 号基站的后继基站改为1 号，如右图所示。 此时4 个基站 的可靠性依次为 30，25，15，10。</p>
</div>
</div>