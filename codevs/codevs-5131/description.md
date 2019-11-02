<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><span style="">一条狭长的纸带被均匀划分出了 n 个格子，格子编号从 1 到 n。每个格子上都染了一种颜色color</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">i</sub><span style="">（用[1，m]当中的一个整数表示），并且写了一个数字number</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">i</sub><span style="">。</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"></span><img height="88" src="/source/codevs/codevs-5131/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01MTMxL2h0dHA6Ly81MndlaWtlLmVpY3AubmV0OjgxL2ltYWdlcy9tZWRpYS91cGxvYWRzL2ltYWdlcy8yMDE1XzExXzhfMTNfMTZfNTUuSlBFRw==.JPEG" style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;" width="500"><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style=""><span style="">定义一种特殊的三元组：(x, y, z)，其中 x，y，z 都代表纸带上格子的编号，这里的三元组要求满足以下两个条件：</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style="">1. x, y, z都是整数,x &lt;y &lt;z,y−x=z−y</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style="">2. color</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">x</sub><span style="">= color<sub style="">z<br></sub>满足上述条件的三元组的分数规定为(x + z) ∗ (number</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">x</sub><span style="">+ number</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">z</sub><span style="">)。整个纸带的分数规定为所有满足条件的三元组的分数的和。这个分数可能会很大，你只要输出整个纸带的分数除以 10,007 所得的余数即可。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">第一行是用一个空格隔开的两个正整数n和m，n代表纸带上格子的个数，m代表纸带上颜色的种类数。</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style="">第二行有n个用空格隔开的正整数，第i个数字number</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">i</sub><span style="">代表纸带上编号为i的格子上面写的数字。</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style="">第三行有n个用空格隔开的正整数，第i个数字color</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">i</sub><span style="">代表纸带上编号为i的格子染的颜色。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: 微软雅黑, &#39;Microsoft YaHei&#39;; font-size: 13px; line-height: 20px; white-space: pre-wrap; background-color: rgb(255, 255, 255); ">共一行，一个整数，表示所求的纸带分数除以 10,007 所得的余数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">输入样例1<br></span></p><p><span style="">6 2</span></p><p><span style="">5 5 3 2 2 2</span></p><p><span style="">2 2 1 1 2 1</span></p><p><span style="">输入样例2</span></p><p><span style="">15 4</span></p><p><span style="">5 10 8 2 2 2 9 9 7 7 5 6 4 2 4</span></p><p><span style="">2 2 3 3 4 3 3 2 4 4 4 4 1 1 1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">输出样例1</span></p><p><span style="">82</span></p><p><span style="">输出样例2</span></p><p><span style="">1388</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">【输入输出样例 1 说明】</span><span style=""><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style="">纸带如题目描述中的图所示。</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style="">所有满足条件的三元组为：(1,3,5),(4,5,6)。</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style="">所以纸带的分数为(1 + 5) ∗ (5 + 2) + (4 + 6) ∗ (2 + 2) = 42 + 40 = 82。</span><br style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;"><span style=""><strong>【数据说明】</strong><br>对于第 1 组至第 2 组数据，1 ≤ n ≤ 100,1 ≤ m ≤ 5；<br>对于第 3 组至第 4 组数据，1 ≤ n ≤ 3000,1 ≤ m ≤ 100；<br>对于第 5 组至第 6 组数据，1 ≤ n ≤ 100000,1 ≤ m ≤ 100000，且不存在出现次数超过 20 的颜色；<br>对 于 全 部 10 组 数 据 ， 1 ≤ n ≤ 100000,1 ≤m ≤ 100000,1 ≤ color</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">i</sub><span style="">≤ m,1 ≤number</span><sub style="font-family: Monaco, Menlo, Consolas, 'Courier New', monospace;">i</sub><span style="">≤ 100000。</span></span></p>
</div>
</div>