<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个点集指一堆点在平面上的点（坐标都是整数）。如果点集A通过任意的旋转，平移，反射和膨胀操作后与点集B重合，那么认为A和B是相同的。</p>
<p>比如：点集{(0,0), (2,0), (2,1)}跟{(6,1), (6,5), (4,5)}相同, 跟{(4,0),(6,0), (5,-1)}不同<strong>。</strong><strong></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入整数K，表示原始点集的点数。</p>
<p>然后输入K行，每行两个整数表示第i个点的坐标。</p>
<p>然后输入n，表示有多少个待比较的点集。</p>
<p>然后对于每个待比较的点集，按照原始点集的输入格式输入。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出n行，每行输出字符串&ldquo;Yes&rdquo;或&ldquo;No&rdquo;，表示是否跟原始点集一样。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>3</p>
<p>0 0</p>
<p>2 0</p>
<p>2 1</p>
<p>2</p>
<p>3</p>
<p>4 1</p>
<p>6 5</p>
<p>4 5</p>
<p>3</p>
<p>4 0</p>
<p>6 0</p>
<p>5 -1</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>Yes</p>
<p>No</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>对于</strong><strong>40%</strong><strong>的数据，有</strong><strong>1</strong><strong>≤每个点集的大小≤</strong><strong>10</strong><strong>。</strong><strong></strong></p>
<p><strong>对于所有的数据，有</strong><strong>1</strong><strong>≤每个点集的大小≤</strong><strong>25000</strong><strong>，坐标绝对值不超过</strong><strong>20001</strong><strong>，</strong><strong>n&lt;=12</strong><strong>。</strong></p>
</div>
</div>