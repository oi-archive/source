<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有<em>n</em>个城市和<em>m</em>条单向道路，城市编号为1~<em>n</em>。每条道路连接两个不同的城市，且任意两条道路要么起点不同要么终点不同，因此<em>n</em>和<em>m</em>满足<em>m</em>&lt;=<em>n</em>(<em>n</em>-1)。</p>
<p>给定两个城市<em>a</em>和<em>b</em>，可以给<em>a</em>到<em>b</em>的所有简单路（所有城市最多经过一次，包括起点和终点）排序：先按长度从小到大排序，长度相同时按照字典序从小到大排序。你的任务是求出<em>a</em>到<em>b</em>的第<em>k</em>短路。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行包含五个正整数<em>n</em>, <em>m</em>, <em>k</em>, <em>a</em>, <em>b</em>。以下<em>m</em>行每行三个整数<em>u</em>, <em>v</em>, <em>l</em>，表示从城市<em>u</em>到城市<em>v</em>有一条长度为<em>l</em>的单向道路。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果<em>a</em>到<em>b</em>的简单路不足<em>k</em>条，输出No，否则输出第<em>k</em>短路：从城市<em>a</em>开始依次输出每个到达的城市，直到城市<em>b</em>，中间用减号"-"分割。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 20 10 1 5</p>
<p>1 2 1</p>
<p>1 3 2</p>
<p>1 4 1</p>
<p>1 5 3</p>
<p>2 1 1</p>
<p>2 3 1</p>
<p>2 4 2</p>
<p>2 5 2</p>
<p>3 1 1</p>
<p>3 2 2</p>
<p>3 4 1</p>
<p>3 5 1</p>
<p>4 1 1</p>
<p>4 2 1</p>
<p>4 3 1</p>
<p>4 5 2</p>
<p>5 1 1</p>
<p>5 2 1</p>
<p>5 3 1</p>
<p>5 4 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1-2-4-3-5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%的数据满足：<em>n</em>&lt;=5</p>
<p>40%的数据满足：<em>n</em>&lt;=30</p>
<p>100%的数据满足：2&lt;=<em>n</em>&lt;=50, 1&lt;=<em>k</em>&lt;=200</p>
</div>
</div>