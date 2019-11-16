<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>花匠栋栋种了一排花，每株花都有自己的高度。花儿越长越大，也越来越挤。栋栋决定把这排中的一部分花移走，将剩下的留在原地，使得剩下的花能有空间长大，同时，栋栋希望剩下的花排列得比较别致。<br>具体而言，栋栋的花的高度可以看成一列整数h_1, h_2, … , h_n。设当一部分花被移走后，剩下的花的高度依次为g_1, g_2, … , g_m，则栋栋希望下面两个条件中至少有一个满足：<br>条件 A：对于所有的1&lt;i&lt;m/2，g_2i &gt; g_2i-1，且g_2i &gt; g_2i+1； <br>条件 B：对于所有的1&lt;i&lt;m/2，g_2i &lt; g_2i-1，且g_2i &lt; g_2i+1。<br>注意上面两个条件在m = 1时同时满足，当m &gt; 1时最多有一个能满足。<br>请问，栋栋最多能将多少株花留在原地。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个整数 n，表示开始时花的株数。<br>第二行包含 n 个整数，依次为h_1, h_2,… , h_n，表示每株花的高度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行，包含一个整数 m，表示最多能留在原地的花的株数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 <br>5 3 2 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20%的数据，n ≤ 10； <br>对于 30%的数据，n ≤ 25； <br>对于 70%的数据，n ≤ 1000，0 ≤ h_i ≤ 1000； <br>对于 100%的数据，1 ≤ n ≤ 100,000，0 ≤ h_i ≤ 1,000,000，所有的h_i随机生成，所有随机数服从某区间内的均匀分布。</p>
</div>
</div>