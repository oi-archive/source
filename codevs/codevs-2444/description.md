<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有<em>n</em>条南北方向的双向街道和<em>n</em>条东西方向的双向街道纵横交错。相邻街道（不管是哪个走向）的距离均为<em>L</em>英里。西南角交叉口的坐标为(1,1)，东北角为(<em>n</em>,<em>n</em>)。在所有交叉口均可任意改变行驶方向。每条街道有它自己的<strong><em><span style="text-decoration: underline;">最高速度</span></em></strong>限制，该限制对整条街道有效（不管行驶方向如何）。</p>
<p>你的任务是从交叉口(<em>x<sub>s</sub></em>,<em>y<sub>s</sub></em>)开车行驶到(<em>x<sub>t</sub></em>,<em>y<sub>t</sub></em>)，要求<strong><em><span style="text-decoration: underline;">只能在交叉口处改变速度</span></em></strong>，行驶过程中不得违反所在街道的速度限制，只能沿着路程最短的线路行驶，并且行驶时间在给定的闭区间[<em>t</em><sub>1</sub>,<em>t</em><sub>2</sub>]内。车速以“每小时英里数”为单位，它必须是5的正整数倍。若车速为<em>v</em>，则每加仑汽油能行驶的英里数为80-0.03<em>v</em><sup>2</sup>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为两个整数<em>n</em>, <em>L</em>, 第二行包含<em>n</em>个正整数，从南到北描述<em>n</em>条东西走向的街道的速度限制，第三行包含<em>n</em>个正整数，从西到东描述<em>n</em>条南北走向的街道的速度限制。第四行包含六个正整数<em>x<sub>s</sub></em>, <em>y<sub>s</sub></em>, <em>x<sub>t</sub></em>, <em>y<sub>t</sub></em>, <em>t</em><sub>1</sub>, <em>t</em><sub>2</sub>.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果无解，输出No，否则输出两行，分别描述最早到达的方案（若有多种方案，选择其中最省油的）和最省油的方案（如果有多种方案，选择其中最早到达的）。每种方案用两个数表示，第一个数表示到达时刻（单位：分钟，向上取整）；第二个数表示耗油量（单位：加仑，四舍五入保留两位小数）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 20</p>
<p>30 40 50 50 50 50</p>
<p>50 50 50 50 50 40</p>
<p>1 1 6 6 300 320</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>300 6.25</p>
<p>318 5.60</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%的数据满足：<em>n</em>&lt;=4</p>
<p>50%的数据满足：<em>n</em>&lt;=8</p>
<p>100%的数据满足：1&lt;=<em>n</em>&lt;=10, 1&lt;=<em>l</em>&lt;=20, 0&lt;=<em>t</em><sub>1</sub>&lt;=<em>t</em><sub>2</sub>&lt;=1000. 速度限制不超过50</p>
</div>
</div>