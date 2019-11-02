<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n个小朋友排成一列。每个小朋友手上都有一个数字。规定每个小朋友的特征值等于他手上的数字。</p><p>作为这些小朋友的老师，你需要给每坨小朋友一个分数，分数是这坨小朋友特征值中的第k小。</p><p>一“坨”小朋友指的是一段连续的小朋友。</p><p>另外，老师也可以修改某个小朋友手上的数字。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个数n，m，type，表示有n个小朋友，m次操作，type取值为0或1。<br></p><p>接下来一行n个数字，表示每个小朋友手上初始的数字。</p><p>接下来m行，每行3个数x，y，k，若x=0，则表示第y个小朋友手上的数字加上k，否则表示询问第x到第y这坨小朋友的分数，（k就是第k小的那个k）</p><p>注意，当type=1时，实际的x=x xor lastans,y=y xor lastans,k=k xor lastans,lastans为上次的答案，初始时为0.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个询问，输出一行表示分数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 10 0</p><p>4 1 4 8 7 4 3 6 5 3</p><p>0 9 5</p><p>0 5 1</p><p>0 6 -2</p><p>0 7 0</p><p>0 4 -3</p><p>3 4 1</p><p>4 9 3</p><p>0 10 -2</p><p>0 10 1</p><p>5 7 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p><p>5</p><p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2%:n,m&lt;=10,type=0;</p><p>另外的4%:n,m&lt;=2000,type=1;</p><p>另外的6%:n,m&lt;=10000,type=1;</p><p>另外的8%:n,m&lt;=66666,type=0;</p><p>另外的10%:n,m&lt;=23333,type=1;</p><p>100%:n,m&lt;=66666,type=0或1.</p><p>在任何时刻小朋友手上的数字都为不大于n的正整数</p>
</div>
</div>