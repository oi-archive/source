<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小 Z 所在的城市有 N 个公交车站，排列在一条长为 N-1 公里的直线上，从左到右依次编号为1到 N，相邻公交车站间的距离均为 1公里。 <br>作为公交车线路的规划者，小 Z调查了市民的需求，决定按以下规则设计线路： <br>1． 设共有K辆公交车，则 1到K 号车站作为始发站，N-K+1到 N号车站作为终点站。 <br>2． 每个车站必须被一辆且仅一辆公交车经停（始发站和终点站也算被经停）。 <br>3． 公交车只能从编号较小的车站驶向编号较大的车站。 <br>4． 一辆公交车经停的相邻两个车站间的距离不得超过P 公里。 <br>注意“经停”是指经过并停车，因经过不一定会停车，故经停与经过是两个不同的概念。<br>在最终确定线路之前，小 Z 想知道有多少种满足要求的方案。由于答案可能很大，你只需求出答案对30031取模的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件只有一行，其中包含用空格隔开的三个正整数N， K，<br>P，分别表示公交车站数，公交车数，一辆公交车经停的相邻两个车站间的最大距离。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个整数，表示满足要求的方案数对30031取模的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 2 4 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>81</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的数据保证40%的数据满足N≤1000。100%的数据满足1&lt;N&lt;10<sup>9</sup>，1&lt;P≤10，K&lt;N，1&lt;K≤P</p>
</div>
</div>