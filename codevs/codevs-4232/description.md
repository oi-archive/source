<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">Byteotian Interstellar Union有N个成员国。现在它发现了一颗新的星球，这颗星球的轨道被分为M份（第M份和第1份相邻），第i份上有第Ai个国家的太空站。</span><span style="FONT-FAMILY: arial, verdana, helvetica, sans-serif;">这个星球经常会下陨石雨。BIU已经预测了接下来K场陨石雨的情况。</span><span style="FONT-FAMILY: arial, verdana, helvetica, sans-serif;">BIU的第i个成员国希望能够收集Pi单位的陨石样本。你的任务是判断对于每个国家，它需要在第几次陨石雨之后，才能收集足够的陨石。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="FONT-FAMILY: arial, verdana, helvetica, sans-serif !important;">第一行是两个数N,M。
第二行有M个数，第i个数Oi表示第i段轨道上有第Oi个国家的太空站。
第三行有N个数，第i个数Pi表示第i个国家希望收集的陨石数量。
第四行有一个数K，表示BIU预测了接下来的K场陨石雨。
接下来K行，每行有三个数Li,Ri,Ai，表示第K场陨石雨的发生地点在从Li顺时针到Ri的区间中（如果Li&lt;=Ri，就是Li,Li+1,...,Ri，否则就是Ri,Ri+1,...,m-1,m,1,...,Li），向区间中的每个太空站提供Ai单位的陨石样本。</pre><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<pre style="font-size: 18px; font-family: arial, verdana, helvetica, sans-serif !important;">N行。第i行的数Wi表示第i个国家在第Wi波陨石雨之后能够收集到足够的陨石样本。如果到第K波结束后仍然收集不到，输出NIE。</pre><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 5<br style="">1 3 2 1 3<br style="">10 5 7<br style="">3<br style="">4 2 4<br style="">1 3 1<br style="">3 5 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br style="">NIE<br style="">1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="FONT-FAMILY: arial, verdana, helvetica, sans-serif;">1&lt;=n,m,k&lt;=3*10^5 1&lt;=Pi&lt;=10^9 1&lt;=Ai&lt;10^9</span></p>
</div>
</div>