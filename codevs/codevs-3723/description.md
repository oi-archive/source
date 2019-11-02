<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style=""><span style="">为了把工厂中高低不等的物品按从低到高排好序，工程师发明了一种排序机械臂。它遵循_个简单的排序规则， </span></span><span style=""><span style="">第一次操作找到最低的物品的位置</span></span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">P1</span></span><span style=""><span style="">，并把左起第一个至</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">P1</span></span><span style=""><span style="">间的物品反序；第二次找到第二低的物品的位置</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">P2, </span></span><span style=""><span style="">并把左起第二个至</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">P2</span></span><span style=""><span style=""><span style="">间的物品反序...最终所有的物品都会被排好序。</span></span></span></p><p style=""><span style=""><span style="">上图给出一个示例，第一次操作前，最低的物品在位置</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">4,</span></span><span style=""><span style="">于是把第</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">1</span></span><span style=""><span style="">至</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">4</span></span><span style=""><span style=""><span style="">的物品反序；第二次操作前，第二低的物 品在位置6,于是把第2至6的物品反序...</span></span></span></p><p style=""><span style=""><span style="">你的任务便是编写一个程序，确定一个操作序列，即每次操作前第</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">i</span></span><span style=""><span style="">低的物品所在位置</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">Pi,</span></span><span style=""><span style="">以便机械臂工作。需要 注意的是，如果有高度相同的物品，必须保证排序后它们的相对位置关系与初始时相同。</span></span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">第一行包含正整数</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">n,</span></span><span style=""><span style=""><span style="">表示需要排序的物品数量。</span></span></span></p><p style=""><span style=""><span style="">第二行包含</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">n</span></span><span style=""><span style="">个空格分隔的整数</span></span><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">ai,</span></span><span style=""><span style="">表示每个物品的高度。</span></span></p><p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="BACKGROUND: none transparent scroll repeat 0% 0%; TEXT-ALIGN: justify; MARGIN: 0px 0px 21px 1px; TEXT-JUSTIFY: inter-ideograph; LINE-HEIGHT: 13px"><span style="COLOR: black"><span style="FONT-SIZE: 12px; FONT-FAMILY: 宋体">输出一行包含</span></span><span style="FONT-SIZE: 12px; COLOR: black"><span style="FONT-FAMILY: Arial Unicode MS">n</span></span><span style="COLOR: black"><span style="FONT-SIZE: 12px; FONT-FAMILY: 宋体">个空格分隔的整数</span></span><span style="FONT-FAMILY: Arial Unicode MS"><span style="FONT-SIZE: 12px; COLOR: black">Pi</span><span style="FONT-SIZE: 12px; COLOR: black">。</span></span></p><p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;"><span style="">6</span></span></span></p><p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">3 4 5 1 6 2</span></span></p><p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;"><span style="">4</span></span></span></p><p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">3 3 2 1</span></span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">4 6 4 5 6 6</span></span></p><p style=""><span style=""><span style="FONT-FAMILY: Arial Unicode MS;">4 2 4 4</span></span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据</p><p>1&lt;n&lt;1000</p><p><br></p><p>对于100%的数据</p><p>  1&lt;n&lt;100000</p><p>  1&lt;ai&lt;2000000000</p><p><br></p><p> </p>
</div>
</div>