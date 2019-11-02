<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>平面上的整点处放着奇数块核仁巧克力饼。Stan先画一条竖线，通过某个核仁巧克力饼。然后，Ollie选择一个被刚才的竖线通过的某个核仁巧克力饼，画一条横线。</p>
<p>这两条线将平面分成了4个部分。Stan得到左下和右上两个部分中所有的核仁巧克力饼，Ollie得到左上和右下两个部分中所有的核仁巧克力饼，两条线上的核仁巧克力饼都不计算在内。</p>
<p>两人知道对方都用最佳策略，即Stan要保证不管Ollie怎样画横线，Stan自己在最坏情况下得到的数量要尽可能大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是n，表示核仁巧克力饼的数量，接下来的n行，每行两个整数，表示坐标，没有两个点重合。n&lt;200000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>按照样例的格式，先输出Stan保证能够得到的最大数量。再输出在这种情况下，Ollie可能得到核仁巧克力饼数量（使用最优策略），从小到大输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11</p>
<p>3 2</p>
<p>3 3</p>
<p>3 4</p>
<p>3 6</p>
<p>2 -2</p>
<p>1 -3</p>
<p>0 0</p>
<p>-3 -3</p>
<p>-3 -2</p>
<p>-3 -4</p>
<p>3 -7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Stan: 7; Ollie: 2 3;</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>