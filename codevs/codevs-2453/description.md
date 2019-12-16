<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>著名的格雷码是指2<sup>n</sup>个不同n位二进制数（即0~2<sup>n</sup>-1，不足n位在前补零）的一个排列，这个排列满足相邻的两个二进制数的n位数字中最多只有一个数字不同（例如003和001就有一个数位不同，而003和030有两个数位不同，不符合条件）。例如n=2时，(00,01,11,10)就是一个满足条件的格雷码。</p>
<p>所谓超级格雷码就是指B<sup>n</sup>个不同的n位B进制数的排列满足上面的条件。</p>
<p>任务：给出n和B（2≤B≤36, 1≤B<sup>n</sup>≤65535），求一个满足条件的格雷码。对于大于9的数位用A~Z表示（10~35）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>只有一行，为两个整数n和B。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一共B<sup>n</sup>个行，每行一个B进制数，表示你所求得的符合条件的排列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>00</pre>
<pre>01</pre>
<pre><span style="">11</span></pre>
<p>  10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2≤B≤36, 1≤B<sup>n</sup>≤65535</p>
</div>
</div>