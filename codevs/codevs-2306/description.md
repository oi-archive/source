<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Elaxia最近迷恋上了空手道，他为自己设定了一套健身计划，比如俯卧撑、仰卧起坐等等，不过到目前为止，他坚持下来的只有晨跑。</p>
<p>现在给出一张学校附近的地图，这张地图中包含N个十字路口和M条街道，Elaxia只能从一个十字路口跑向另外一个十字路口，街道之间只在十字路口处相交。Elaxia每天从寝室出发跑到学校，保证寝室编号为1，学校编号为N。</p>
<p>Elaxia的晨跑计划是按周期（包含若干天）进行的，由于他不喜欢走重复的路线，所以在一个周期内，每天的晨跑路线都不会相交（在十字路口处），寝室和学校不算十字路口。Elaxia耐力不太好，他希望在一个周期内跑的路程尽量短，但是又希望训练周期包含的天数尽量长。</p>
<p>除了练空手道，Elaxia其他时间都花在了学习和找MM上面，所有他想请你帮忙为他设计一套满足他要求的晨跑计划。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：两个数N,M。表示十字路口数和街道数。</p>
<p>接下来M行，每行3个数a,b,c，表示路口a和路口b之间有条长度为c的街道（单向）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两个数，第一个数为最长周期的天数，第二个数为满足最长天数的条件下最短的路程长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 10</p>
<p>1 2 1</p>
<p>1 3 1</p>
<p>2 4 1</p>
<p>3 4 1</p>
<p>4 5 1</p>
<p>4 6 1</p>
<p>2 5 5</p>
<p>3 6 6</p>
<p>5 7 1</p>
<p>6 7 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，N ≤ 20，M ≤ 120。</p>
<p>对于100%的数据，N ≤ 200，M ≤ 20000。</p>
</div>
</div>