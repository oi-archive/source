<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>奸商<span style="font-family: Verdana;">zn</span><span style="">（请勿对号入座）开办了一家火车公司，弱弱的板猪要去看望她的朋友小板猪，万恶的</span><span style="font-family: Verdana;">zn</span><span style="">对板猪实施各种提高价，板猪不寒而栗。。。</span></span></p>
<p><span>铁路线上有<span style="font-family: Verdana;">n(2&lt;=n&lt;=10000)</span><span style="">个火车站，每个火车站到该线路的首发火车站距离都是已知的。任意两站之间的票价如下表所示：</span></span></p>
<p><span>站之间的距离 <span style="font-family: Verdana;">- X </span><span style="">　　　　 票价</span></span></p>
<p><span>0&lt;X&lt;=L1<span style="">　　　　   </span><span style="font-family: Verdana;">C1</span></span></p>
<p><span>L1&lt;X&lt;=L2</span><span>         </span><span> C2</span></p>
<p><span>L2&lt;X&lt;=L3</span><span>         </span><span> C3</span></p>
<p><span>其中<span style="font-family: Verdana;">L1</span><span style="">，</span><span style="font-family: Verdana;">L2</span><span style="">，</span><span style="font-family: Verdana;">L3</span><span style="">，</span><span style="font-family: Verdana;">C1</span><span style="">，</span><span style="font-family: Verdana;">C2</span><span style="">，</span><span style="font-family: Verdana;">C3</span><span style="">都是已知的正整数，且</span><span style="font-family: Verdana;">(1 &lt;= L1 &lt; L2 &lt; L3 &lt;= 10^9, 1 &lt;= C1 &lt; C2 &lt; C3 &lt;= 10^9)</span><span style="">。显然若两站之间的距离大于</span><span style="font-family: Verdana;">L3</span><span style="">，那么从一站到另一站至少要买两张票。注意：每一张票在使用时只能从一站开始到另一站结束。</span></span></p>
<p><span>现在板猪要从<span style="font-family: Verdana;">A</span><span style="">到</span><span style="font-family: Verdana;">B</span><span style="">，为了不让奸商</span><span style="font-family: Verdana;">zn</span><span style="">敲竹杠，你能帮助板猪吗？</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件的第一行为<span style="font-family: Verdana;">6</span><span style="">个整数</span><span style="font-family: Verdana;">, L1, L2, L3, C1, C2, C3 (1 &lt;= L1 &lt; L2 &lt; L3 &lt;= 10^9, 1 &lt;= C1 &lt; C2 &lt; C3 &lt;= 10^9) ,</span><span style="">这些整数由空格隔开</span><span style="font-family: Verdana;">.</span><span style="">第二行为火车站的数量</span><span style="font-family: Verdana;">N (2 &lt;= N &lt;= 10000).</span><span style="">第三行为两个不同的整数</span><span style="font-family: Verdana;">A</span><span style="">、</span><span style="font-family: Verdana;">B,</span><span style="">由空格隔开。接下来的 </span><span style="font-family: Verdana;">N-1 </span><span style="">行包含从第一站到其他站之间的距离</span><span style="font-family: Verdana;">.</span><span style="">这些距离按照增长的顺序被设置为不同的正整数。相邻两站之间的距离不超过</span><span style="font-family: Verdana;">L3. </span><span style="">两个给定火车站之间行程花费的最小值不超过</span><span style="font-family: Verdana;">10^9</span><span style="">，而且任意两站之间距离不超过 </span><span style="font-family: Verdana;">10^9</span><span style="">。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>&nbsp; &nbsp;输出文件中只有一个数字<span style="font-family: Verdana;">,</span><span style="font-family: 宋体;">表示从</span><span style="font-family: Verdana;">A</span><span style="font-family: 宋体;">到</span><span style="font-family: Verdana;">B</span><span style="font-family: 宋体;">要花费的最小值</span><span style="font-family: Verdana;">.</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 6 8 20 30 40</span></p>
<p><span>7</span></p>
<p><span>2 6</span></p>
<p><span>3</span></p>
<p><span>7</span></p>
<p><span>8</span></p>
<p><span>13</span></p>
<p><span>15</span></p>
<p><span>23</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>70</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p> </p>
</div>
</div>
</div>