<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>《三体》第一部中，主持纳米材料研究的材料物理学博士汪淼在接触“科学边界”组织后发现自己的视网膜被某种神秘的力量投影出一个倒计时。“科学边界”负责人申玉菲告诉他，只有停下纳米材料项目研究，才能使倒计时暂时停止。</p><p>（以下开始胡扯）</p><p>为了躲神秘避倒计时带来的恐惧，汪淼将之后的研究进程列成了一张表，表示倒计时出现后的第几天几时几分几秒，项目研究会因故停止，以及什么时候研究再度开始。（在项目研究停止的时间段中，倒计时也会暂时停止）现在汪淼想知道，倒计时出现后的第几天几时几分几秒，倒计时会变成0000:00:00。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，表示倒计时的起点，格式为“XXXX:XX:XX”(输入无引号，X表示0~9的数字)</p><p>第二行，表示倒计时开始时现实时间，格式为“XX:XX:XX”(输入无引号，X表示0~9的数字)</p><p>之后若干行，每行八个数，分别表示倒计时出现后的第几天、几时、几分、几秒项目研究停止，以及倒计时出现后的第几天、几时、几分、几秒项目研究再度开始，格式为“Day d1 XX:XX:XX~Day d2 XX:XX:XX”(输入无引号，d1,d2为整型数，X表示0~9的数字)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行四个数，表示第几天，表示几时、几分、几秒，格式为“Day d XX:XX:XX”(输出无引号，d为整型数，X表示0~9的数字)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1200:00:00</p><p>00:00:00</p><p>Day 2 01:39:25~Day 3 01:39:25<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Day 52 00:00:00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>题中给出的所有量不超过maxint(2^15-1)，且测试数据组数不超过100</p>
</div>
</div>