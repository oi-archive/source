<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>yh最近迷上了油画 。一天，好朋友ywm来到yh家，yh便决定当场画上一幅。</p>
<p>完成一幅油画需要涂色n次，每次需要用的颜色编号为a[i]，一种颜色可能被多次使用。</p>
<p>yh的调色盘大小有限，最多只能存放m种不同色颜料，且初始时颜料盘中装有的颜料编号为1,2,…,m。</p>
<p>每次涂色时，如果当前需要的颜料恰好在yh的调色盘中，yh可以继续画。否则的话，yh需要朋友ywm帮忙取来当前所需的颜料，并考虑在完成本次涂色后，是否保留该种颜色的颜料。如果要保留，则需要从调色盘已有的颜色中选出一种洗掉，来为新加入的颜色空出位置。</p>
<p>由于ywm是客人，yh不想总是麻烦他，于是，他想让你帮忙计算，最少让ywm帮忙多少次可以完成yh的油画？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数，n,m,完成油画共要涂色n次；调色盘最多能装m种不同颜色的颜料，且初始的颜料编号为1-m。</p>
<p>第二行共n个数，表示第i次需要用的颜色a[i]。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出1行，ywm需要帮忙的最少次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11 3</p>
<p>4 1 2 1 5 3 4 4 1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，n≤200000,m≤100000,a[i] ≤2000000</p>
</div>
</div>