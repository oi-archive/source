<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       给定一张有向图，每条边都有一个容量<em>C</em>和一个扩容费用<em>W</em>。这里扩容费用是指将容量扩大1所需的费用。求：</p>
<p>1、  在不扩容的情况下，1到<em>N</em>的最大流；</p>
<p>2、  将1到<em>N</em>的最大流增加<em>K</em>所需的最小扩容费用。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件的第一行包含三个整数<em>N</em>,<em>M</em>,<em>K</em>，表示有向图的点数、边数以及所需要增加的流量。</p>
<p>       接下来的<em>M</em>行每行包含四个整数<em>u</em>,<em>v</em>,<em>C</em>,<em>W</em>，表示一条从<em>u</em>到<em>v</em>，容量为<em>C</em>，扩容费用为<em>W</em>的边。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;输出文件一行包含两个整数，分别表示问题1和问题2的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 8 2</p>
<p>1 2 5 8</p>
<p>2 5 9 9</p>
<p>5 1 6 2</p>
<p>5 1 1 8</p>
<p>1 2 8 7</p>
<p>2 5 4 9</p>
<p>1 2 1 1</p>
<p>1 4 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13 19</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>       30%的数据中，<em>N</em>&lt;=100</p>
<p>       100%的数据中，<em>N</em>&lt;=1000，<em>M</em>&lt;=5000，<em>K</em>&lt;=10</p>
</div>
</div>