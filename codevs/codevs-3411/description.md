<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小浣熊松松和朋友到野外露营，没想到遇上了&amp;pi;年一次的大洪水，好在松松是一只爱观察的小浣熊，他发现露营地的地形和洪水有如下性质：</p><p>①露营地可以被看做是一个N*M的矩形方阵，其中左上角坐标为(1,1)，右下角坐标为(n,m)，每个格子(i,j)都有一个高度h(i,j)。</p><p>②洪水送(r,c)开始，如果一个格子被洪水淹没，那这个格子四周比它低（或相同）的格子也会被淹没。</p><p>现在松松想请你帮忙算算，有多少个格子不会被淹没，便于他和朋友逃脱。</p><p>【原有误数据已删除】</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数n，m，表示矩形方阵右下角坐标。</p><p>以下n行，每行m个数，第i行第j个数表示格子(i,j)的高度。</p><p>最后一行包含两个整数r，c，表示最初被洪水淹没的格子。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行，为永远不会被淹没的格子的数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>1 2 3</p><p>2 3 4</p><p>3 4 5</p><p>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于90%的数据，保证随机生成。</p><p>对于100%的数据，1&lt;=N,M&lt;=1000。</p>
</div>
</div>