<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">【感谢段少提供题目】SN省风流倜傥玉树临风的段少有很多妹子，现在妹子们排成两行，每一行都有</span><span style="">n</span><span style="">个o妹子，每行中相邻两个妹子之间都有绳子相连，长度为给出的值。现在段少需要添加</span><span style="">k</span><span style="">条垂直的绳子来使这两行妹子连通（即从第一行的</span><span style="">i</span><span style="">号妹子连向第二行的</span><span style="">i</span><span style="">号妹子）。所有添加的绳子的长度均为</span><span style="">0</span><span style="">。现在定义一群妹子的征服难度为任意两个妹子最短路距离的最大值（即</span><span style="">max{min_distance(i,j),i</span><span style="">∈</span><span style="">V,j</span><span style="">∈</span><span style="">V}</span><span style="">）。由于妹子太多段少数不过来，请你帮段少安排这</span><span style="">k</span><span style="">个边，使得这群妹子的征服难度尽可能小。输出这个最小值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入共</span><span style="">3</span><span style="">行。第一行包含一个正整数</span><span style="">n和<span style="">正整数</span>k</span><span style="">。第二行和第三行均包含</span><span style="">n-1</span><span style="">个整数，第</span><span style="">i</span><span style="">个整数代表</span><span style="">i</span><span style="">号妹子和</span><span style="">i+1</span><span style="">号妹子之间绳子的长度。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:16px;font-family:宋体">一行，输出最小的征服难度。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 4</p><p>2 1 1 1 2</p><p>1 9 1 9 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">2&lt;=n&lt;=11</span></p><p><span style="">1&lt;=k&lt;=n</span></p><p><span style="">0&lt;=</span><span style="">边权</span><span style="">&lt;=50</span></p><p><br></p>
</div>
</div>