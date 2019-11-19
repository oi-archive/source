<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">lice</span></span><span style=""><span style="">和</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">Bob</span></span><span style=""><span style="">居住在一个由</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">N</span></span><span style=""><span style="">座岛屿组成的国家，岛屿被编号为</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">0</span></span><span style=""><span style="">到</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">N-1。</span></span><span style=""><span style=""><span style="">某些岛屿之间有桥相连，桥上的道路是双 向的，但一次只能供一人通行。其中一些桥由于年久失修成为危桥，最多只能通行两次。</span></span></span></p><p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">Alice</span></span><span style=""><span style="">希望在岛</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">111</span></span><span style=""><span style="">与</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">a1</span></span><span style=""><span style="">和</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">a2</span></span><span style=""><span style="">之间往返</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">an</span></span><span style=""><span style="">次（从</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">a1</span></span><span style=""><span style="">到</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">a2</span></span><span style=""><span style="">再从</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">a2</span></span><span style=""><span style="">到</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">a1</span></span><span style=""><span style="">算一次往返）。同时，</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">Bob</span></span><span style=""><span style="">希望在岛</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">111</span></span><span style=""><span style="">与</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">b1</span></span><span style=""><span style="">和</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">b2</span></span><span style=""><span style="">之间 往返</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">bn</span></span><span style=""><span style="">次。这个过程中，所有危桥最多通行两次，其余的桥可以无限次通行。请问</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">Alice</span></span><span style=""><span style="">和</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">Bob</span></span><span style=""><span style=""><span style="">能完成他们的愿望吗？</span></span></span></p><p style=""> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style=""><span style="">本题有多组测试数据。</span></span></span></p><p style=""><span style=""><span style="">每组数据第一行包含</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">7</span></span><span style=""><span style="">个空格隔开的整数，分别为</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;"><span style="">N、a1、a2、an、b1、b2、bn。</span></span></span></p><p style=""><span style=""><span style="">接下来是一个</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">N</span></span><span style=""><span style="">行</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">N</span></span><span style=""><span style="">列的对称矩阵，由大写字母组成。矩阵的</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">i</span></span><span style=""><span style="">行</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">j</span></span><span style=""><span style="">列描述编号</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">i-1</span></span><span style=""><span style="">和</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">j-1</span></span><span style=""><span style="">的岛屿间的连接情況，若 为</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">“〇”</span></span><span style=""><span style="">则表示有危桥相连；为</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">“N”</span></span><span style=""><span style="">表示有普通的桥相连；为</span></span><span style="FONT-FAMILY: Arial Unicode MS;"><span style="">“</span><span style="">X”</span></span><span style=""><span style="">表示没有桥相连。</span></span></p><p> </p><p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="BACKGROUND: none transparent scroll repeat 0% 0%; TEXT-ALIGN: justify; MARGIN: 0px 0px 21px 1px; TEXT-JUSTIFY: inter-ideograph; LINE-HEIGHT: 13px"><span style="COLOR: black"><span style="FONT-SIZE: 12px; FONT-FAMILY: 宋体">对于每组测试数据输出一行，如果他们都能完成愿望输出</span></span><span style="FONT-SIZE: 12px; COLOR: black"><span style="FONT-FAMILY: Arial Unicode MS">“Yes</span></span><span style="FONT-FAMILY: 宋体"><span style="COLOR: black"><span style="FONT-SIZE: 12px">”，</span></span><span style="COLOR: black"><span style="FONT-SIZE: 12px">否则输出</span></span></span><span style="FONT-SIZE: 12px; COLOR: black"><span style="FONT-FAMILY: Arial Unicode MS">“No”。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 0 1 1 2 3 1</p><p>XOXX</p><p>OXOX</p><p>XOXO</p><p>XXOX</p><p>4 0 2 1 1 3 2</p><p>XNXO</p><p>NXOX</p><p>XOXO</p><p>OXOX</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">Yes</span></span></p><p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;"> No</span></span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<ul style=""><li><p>4≤N≤50</p></li><li><p>0≤a1, a2, b1, b2≤N-1</p></li><li><p>1≤an, bn≤50</p></li></ul>
</div>
</div>