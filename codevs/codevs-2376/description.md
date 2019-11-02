<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>公元3000年，地球联盟已经攻占了银河系内的<em>N</em>个星球，出于资金的考虑，政府仅仅在星球间建立了<em>N</em>-1条双向时空隧道保证任意两个星球之间互相可达。出于管理上的考虑，第<em>i</em>个星球的行政长官要求每个公民在一年内不得从该星球利用时空隧道次数超过<em>H<sub>i</sub></em>次（<strong><span style="text-decoration: underline;">这一统计是基于离开次数统计的，如果你已经使用从该星球离开过</span></strong><strong><em><span style="text-decoration: underline;">H<sub>i</sub></span></em></strong><strong><span style="text-decoration: underline;">次，那么这一年内你就不能再使用时空隧道离开这个星球了</span></strong>）。Louis Paosen是一个星际旅行家，他希望能使用尽量多次的时空隧道，但又不希望最终被迫定居的星球条件太过恶劣。所以他希望能知道对于每个星球<em>i</em>，若从0号星球出发，最终以<em>i</em>号星球为终点，这样的星际旅行途中最多可以使用多少次时空隧道。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数<em>N</em>。接下来的一行包含<em>N</em>个整数<em>H<sub>i</sub></em>，分别表示每个星球的离开次数限制。接下来<em>N</em>-1行每行两个整数，表示这两个星球之间有时空隧道连接。星球的编号从0开始，Louis Paosen一开始在0号星球。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件包含<em>N</em>行，每行一个整数，表示如果最终旅行结束在这个星球，最多可以使用时空隧道的次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>2 6 2</p>
<p>0 1</p>
<p>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>
<p>7</p>
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>40%的数据N≤500</p>
<p>100%的数据中<em>N</em>≤50000。</p>
<p>所有星球的离开次数限制满足1≤<em>H<sub>i</sub></em>≤40000，且每个星球的<em>H<sub>i</sub></em>大于等于与该星球直接相连的星球数（即度数）。<strong></strong></p>
</div>
</div>