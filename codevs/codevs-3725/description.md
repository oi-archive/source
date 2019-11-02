<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">新机房快要建好了，但是当正在装软件的时候，突然有黑客入侵，但是就在那时，插网线的房间</span><span style="">钥匙丢了</span><span style="">..</span><span style="">。所以</span><span style="">haild</span><span style="">和</span><span style="">mulading</span><span style="">开始做防御机房的工作，</span><span style=""><span style="">halid</span></span><span style="">不停的巡察各台电脑，并且在第一</span><span style="">时间告诉</span><span style="">mulading</span><span style="">现在那台机器正在被入侵，不过，由于网速太慢和网线不够，只能一台一台的</span><span style="">建立防御。同时，黑客也在不停的更换入侵的主机，但是入侵一台主机需要时间，如果在入侵成</span><span style="">功之前，</span><span style="">halid</span><span style="">已经到达了这台主机</span><span style="">(</span><span style="">包括同时到达</span><span style="">)</span><span style="">，那么这次的入侵失败。否则，入侵成功。</span><span style="">现在请你编写一个程序，计算出黑客的每一次入侵是否成功。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行：计算机的个数。</span><span style="">(3&lt;=n&lt;=100) </span></p><p><span style="">第</span><span style="">2</span><span style="">～</span><span style="">n+1</span><span style="">行：一个邻接矩阵，告诉你每两台计算机的距离。当然，对角线将会是</span><span style="">0</span><span style="">，因为不会有</span></p><p><span style="">计算机和自己相连。每个数字不超过</span><span style="">100000</span><span style="">。</span> </p><p><span style="">第</span><span style="">n+2</span><span style="">行：一个整数</span><span style="">N</span><span style="">，表示黑客入侵的次数。</span><span style="">N&lt;=4000 </span></p><p><span style="">接下来</span><span style="">N</span><span style="">行</span><span style="">:</span><span style="">三个整数</span><span style="">,</span><span style="">分别表示黑客第</span><span style="">i</span><span style="">次入侵时</span><span style="">,halid</span><span style="">的位置</span><span style="">,</span><span style="">黑客准备入侵的位置</span><span style="">,</span><span style="">和黑客</span></p><p><span style="">入侵成功需要的时间。</span> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:13px;font-family: ÐÂËÎÌå">N</span><span style="font-size:13px;font-family:新宋体">行</span><span style="font-size:13px;font-family:ÐÂËÎÌå">: </span></p><p><span style="font-size:13px;font-family:新宋体">第</span><span style="font-size:13px;font-family:ÐÂËÎÌå">i</span><span style="font-size:13px;font-family:新宋体">行表示黑客第</span><span style="font-size:13px;font-family:ÐÂËÎÌå">i</span><span style="font-size:13px;font-family:新宋体">次入侵的状态，如果成功，输出</span><span style="font-size:13px;font-family:ÐÂËÎÌå">S</span><span style="font-size:13px;font-family:新宋体">，不成功，输出</span><span style="font-size:13px;font-family:ÐÂËÎÌå">F</span><span style="font-size:13px;font-family:新宋体">。</span> </p><p><span style="font-size:13px;font-family: ÐÂËÎÌå">&nbsp;</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 </span></p><p><span style="">0 4 9 21 </span></p><p><span style="">4 0 8 17 </span></p><p><span style="">9 8 0 16 </span></p><p><span style="">21 17 16 0 </span></p><p><span style="">2 </span></p><p><span style="">1 2 5 </span></p><p><span style="">3 4 2 </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">F </span></p><p><span style="">S </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">N&lt;=4000 每两台的机子之间的距离小于等于<span style="">100000</span></span></p>
</div>
</div>