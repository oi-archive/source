<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>政府在某山区修建了一条道路，恰好穿越总共m个村庄的每个村庄一次，没有回路或交叉，任意两个村庄只能通过这条路来往。已知任意两个相邻的村庄之间的距离
为di（为正整数），其中，0 &lt; i &lt; m。为了提高山区的文化素质，政府又决定从m个村中选择n个村建小学（设 0 &lt; n
&lt; = m &lt; 500
）。请根据给定的m、n以及所有相邻村庄的距离，选择在哪些村庄建小学，才使得所有村到最近小学的距离总和最小，计算最小值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行为m和n，其间用空格间隔<br>第2行为(m-1) 个整数，依次表示从一端到另一端的相邻村庄的距离，整数之间以空格间隔。</p><p><br></p><p>例如<br>10 3<br>2 4 6 5 2 4 3 1 3(样例输入)<br>表示在10个村庄建3所学校。</p><p>第1个村庄与第2个村庄距离为2，</p><p>第2个村庄与第3个村庄距离为4，</p><p>第3个村庄与第4个村庄距离为6，</p><p>...，</p><p>第9个村庄到第10个村庄的距离为3。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>各村庄到最近学校的距离之和的最小值。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">10  2</p><p style="">3  1  3  1  1  1  1  1  3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>18<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0 &lt; n
&lt; = m &lt; 500<br></p>
</div>
</div>