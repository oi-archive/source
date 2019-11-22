<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>a180285 非常喜欢滑雪。他来到一座雪山，这里分布着 M 条供滑行的轨道和 N 个轨道之间的交点（同时也是景点），而且每个景点都有一编号 i（1&lt;=i&lt;=N）和一高度Hi。a180285能从景点i滑到景点j当且仅当存在一条 i和 j之间的边，且 i的高度不小于j。 <br>与其他滑雪爱好者不同，a180285喜欢用最短的滑行路径去访问尽量多的景点。如果仅仅访问一条路径上的景点，他会觉得数量太少。于是 a180285拿出了他随身携带的时间胶囊。<br>这是一种很神奇的药物，吃下之后可以立即回到上个经过的景点（不用移动也不被认为是a180285 滑行的距离）。请注意，这种神奇的药物是可以连续食用的，即能够回到较长时间之前到过的景点（比如上上个经过的景点和上上上个经过的景点）。 <br>现在，a180285站在1号景点望着山下的目标，心潮澎湃。他十分想知道在不考虑时间胶囊消耗的情况下，以最短滑行距离滑到尽量多的景点的方案（即满足经过景点数最大的前提下使得滑行总距离最小）。你能帮他求出最短距离和景点数吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是两个整数N，M。 <br>接下来1行有N个整数 Hi，分别表示每个景点的高度。 <br>接下来 M 行，表示各个景点之间轨道分布的情况。每行 3 个整数，Ui，Vi，Ki。表示编号为Ui的景点和编号为Vi的景点之间有一条长度为 Ki的轨道。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行，表示a180285最多能到达多少个景点，以及此时最短的滑行距离总和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 <br>3 2 1 <br>1 2 1 <br>2 3 1 <br>1 3 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 2 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，保证 1&lt;=N&lt;=2000 <br> 对于100%的数据，保证 1&lt;=N&lt;=100000 <br>对于所有的数据，保证 1&lt;=M&lt;=1000000，1&lt;=Hi&lt;=1000000000，1&lt;=Ki&lt;=1000000000。</p>
</div>
</div>