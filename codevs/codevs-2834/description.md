<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小<span style="font-family: 'Times New Roman';">X</span><span style="">是个聪明的孩子，他记得斐波那契数列f(n)</span>中前<span style="font-family: 'Times New Roman';">1000</span><span style="">个数。不过由于学业的压力，他无法记得每一个数在数列中的位置。</span></p>
<p><span style="">他现在知道<span>斐波那契数列</span>中的一个数f(x)</span>模<span style="font-family: 'Times New Roman';">P</span><span style="">后的值</span><span style="font-family: 'Times New Roman';">N（即f(x) mod P=N）</span>以及<span style="font-family: 'Times New Roman';">x</span><span style="">可能的最大值</span><span style="font-family: 'Times New Roman';">M</span><span style="">，如果再对于斐波那契数列中每一个数都模</span><span style="font-family: 'Times New Roman';">P</span><span style="">，他想知道这个数可能出现在第几个。不过小</span><span style="font-family: 'Times New Roman';">X</span><span style="">还要做作业呢，这个问题就交给你由编程来解决了。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一行，共<span style="font-family: 'Times New Roman';">3</span><span style="">个整数，第一个数为</span><span style="font-family: 'Times New Roman';">N</span><span style="">，第二个数为</span><span style="font-family: 'Times New Roman';">P</span><span style="">，第三个数为</span><span style="font-family: 'Times New Roman';">x</span><span style="">可能的最大值</span><span style="font-family: 'Times New Roman';">M</span><span style="">，三个数以空格隔开。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>一个整数，满足f(i) mod P = N</span><span>的最小的<span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">，如果不存在则输出</span><span style="font-family: 'Times New Roman';">-1</span><span style="font-family: 宋体;">。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 7 5</span></p>

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
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span>≤50</p>
<p>对于<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span>≤100</p>
<p>对于<span style="font-family: 'Times New Roman';">70%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span>≤500</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span>≤1000，0≤N&lt;P<span style="">，</span><span style="font-family: 'Times New Roman';">P</span><span style="">为素数且</span><span style="font-family: 'Times New Roman';">2&lt;P&lt;10</span>5。</p>
</div>
</div>