<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>The organizers of CEOI 2011 are planning to hold a party with lots of balloons. There will be n balloons, all<br>sphere-shaped and lying in a line on the ﬂoor.<br>The balloons are yet to be inﬂated, and each of them initially has zero radius. Additionally, the i-th balloon<br>is permanently attached to the ﬂoor at coordinate xi. They are going to be inﬂated sequentially, from left to<br>right. When a balloon is inﬂated, its radius is increased continuously until it reaches the upper bound for the<br>balloon, ri, or the balloon touches one of the previously inﬂated balloons.</p>
<p>The organizers would like to estimate how much air will be needed to inﬂate all the balloons. You are to<br>ﬁnd the ﬁnal radius for each balloon.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of the standard input contains one integer n (1 ¬ n ¬ 200 000) — the number of balloons.<br>The next n lines describe the balloons. The i-th of these lines contains two integers xi and ri (0 ¬ xi ¬ 109,<br>1 ¬ ri ¬ 109). You may assume that the balloons are given in a strictly increasing order of the x coordinate.<br>In test data worth 40 points an additional inequality n ¬ 2 000 holds.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Your program should output exactly n lines, with the i-th line containing exactly one number &mdash; the radius<br />of the i-th balloon after inﬂating. Your answer will be accepted if it diﬀers from the correct one by no more<br />than 0.001 for each number in the output.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>0 9<br>8 1<br>13 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9.000<br>1.000<br>4.694</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>In test data worth 40 points an additional inequality n ¬ 2 000 holds.</p>
</div>
</div>