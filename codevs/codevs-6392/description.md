<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>摆放汉诺塔的寺院里新来了一位身强力壮的僧侣，他将要接管汉诺塔的移动。每一块金片都很重，最左边的A柱上从上到下依次摆放着编号、重量从1到n的n块金片。这位僧人可以一次性搬起一个柱子顶端、总重量不超过m的一堆金片移到另一个柱子上，且保证小的金片在大的上面。现在他想知道，要怎样搬才能尽快完成任务，把所有金片借助中间的B柱，全部移到右边的C柱上。</p><p>如果有多种最快方案，他想在体力充沛的开始的时候，搬起尽可能重的金片。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入一行，两个整数n和m，用空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行为一个整数t，表示最少搬动次数。</p><p>第二至t+1行，每行格式如下：</p><p>i个整数，表示该次移动的i个金片编号（从小到大），中间用空格隔开；两个柱子编号，表示从前一个柱子移动到后一个柱子，中间用空格隔开。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>1 2 A B</p><p>3 A C</p><p>1 2 B C</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=100,n&lt;=m&lt;=500,t&lt;=200000。</p>
</div>
</div>