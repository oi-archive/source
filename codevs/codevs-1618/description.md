<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>战线可以看作一个长度为 n 的序列，现在需要在这个序列上建塔来防守敌<br>兵，在序列第 i号位置上建一座塔有 Ci 的花费，且一个位置可以建任意多的塔<br>费用累加计算。有 m个区间[L1, R1], [L2, R2], …, [Lm, Rm]，在第 i 个区间<br>的范围内要建至少 Di座塔。求最少花费。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个数n,m。<br>接下来一行，有 n个数，描述 C数组。<br>接下来 m行，每行三个数 Li,Ri,Di，描述一个区间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一行，一个数，为最少花费。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3<br>1 5 6 3 4<br>2 3 1<br>1 5 4<br>3 5 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>位置 1建 2个塔，位置 3建一个塔，位置 4建一个塔。花费 1*2+6+3=11。<br><br></p>
<p>对于 20%的数据，n≤20，m≤20。<br>对于 50%的数据（包括上部分的数据），Di 全部为1。<br>对于 70%的数据（包括上部分的数据），n≤100，m≤1000。<br>对于 100%的数据，n≤1000，m≤10000，1≤Li≤Ri≤n，其余数据均≤10000。</p>
<p> </p>
</div>
</div>