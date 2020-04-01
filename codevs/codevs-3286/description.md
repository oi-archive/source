<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>涵涵有两盒火柴，每盒装有 n 根火柴，每根火柴都有一个高度。现在将每盒中的火柴各自排成一列，同一列火柴的高度互不相同，两列火柴之间的距离定义为：<img height="42" src="../../../media/image/problem/3286.png" width="158"><br>，其中 a<sub>i</sub>表示第一列火柴中第 i 个火柴的高度，b<sub>i</sub>表示第二列火柴中第 i 个火柴的高度。<br>每列火柴中相邻两根火柴的位置都可以交换，请你通过交换使得两列火柴之间的距离最小。请问得到这个最小的距离，最少需要交换多少次？<strong>如果这个数字太大，请输出这个最小交换次数对 99,999,997 取模的结果。</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共三行，第一行包含一个整数 n，表示每盒中火柴的数目。<br>第二行有 n 个整数，每两个整数之间用一个空格隔开，表示第一列火柴的高度。<br>第三行有 n 个整数，每两个整数之间用一个空格隔开，表示第二列火柴的高度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共一行，包含一个整数，表示<strong>最少交换次数对 99,999,997 取模的结果。</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>4 <br>2 3 1 4 <br>3 2 1 4<br>[Sample 2]<br>4 <br>1 3 4 2 <br>1 7 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>1<br>[Sample 2]<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例1说明】<br>最小距离是 0，最少需要交换 1 次，比如：交换第 1 列的前 2 根火柴或者交换第 2 列的前 2 根火柴。<br>【样例2说明】<br>最小距离是 10，最少需要交换 2 次，比如：交换第 1 列的中间 2 根火柴的位置，再交换第 2 列中后 2 根火柴的位置。<br>【数据范围】<br>对于 10%的数据， 1 ≤ n ≤ 10； <br>对于 30%的数据，1 ≤ n ≤ 100； <br>对于 60%的数据，1 ≤ n ≤ 1,000； <br>对于 100%的数据，1 ≤ n ≤ 100,000，0 ≤火柴高度≤ 2^31 - 1。</p>
</div>
</div>