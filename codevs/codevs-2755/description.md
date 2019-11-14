<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一条无限长的路上，有一排无限长的路灯，编号为 1，2，3，4，…… 每盏灯只有两种可能的状态，开或者关。如果按下某一盏灯的开关，那么这盏灯的状态将发生改 变。如果原来开，将变成关。如果原来是关，将变成开。 在刚开始的时候，所有的灯都是关的。每次可以进行如下操作： 指定两个数 a，t（a 为实数，t 为正整数）。将编号为[a]、[2*a]、[3*a] ……[t*a]的灯的 开关各按一次。其中[k]表示实数 k 的整数部分。 在进行了 n 次操作后，发现只有一盏灯是开的，请计算出这盏灯的编号。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数 n，表示 n 次操作。 接下来有 n 行，每行两个数 a_i，t_i。其中 a_i 是实数，小数点后一定有 6 位，t_i 为正整 数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>3 1.618034 13 2.618034 7 1.000000 21一个整数，表示那盏开着的灯的编号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p> 1.618034 13</p>
<p> 2.618034 7</p>
<p>1.000000 21</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>记T = t_1+t_2+t_3+……+t_n</p>
<p>对于30%的数据，满足T≤1000</p>
<p>对于80%的数据，满足T≤200,000</p>
<p>对于100%的数据，满足T≤2,000,000</p>
<p>对于100%的数据，满足n≤5000，1≤a_i&lt;1000，1≤t_i≤T</p>
<p>输入数据保证，在经过n 次操作后，有且只有一盏灯是开着的。</p>
</div>
</div>