<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">有一个形状为n*n矩形的迷宫，入口和出口依次位于左上角和右上角。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">请编程找出所有在迷宫中从入口（左上角）到出口（右上角）的不重复路径，并输出路径总数。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">处于迷宫中时，可选择周围八个方向行走。当前进方格中数字为0时，表示可通过；数字为1时，表示不可通过。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第1行有一个整数n，表示迷宫的大小。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第2到n+1行，每行有n个数字，表示迷宫中的数字。</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; text-decoration: line-through;">数据保证入口与出口的数字不为1。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);">输出1行一个整数，表示从出口到入口的路径总数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">[输入样例1]<br style="">3<br style="">0 0 0<br style="">0 1 1<br style="">1 0 0</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">[输入样例2]<br style="">3<br style="">0 1 0<br style="">1 1 0<br style="">0 0 0</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">对于100%的数据，n≤5。</p><p>然而，你会信吗？~~</p><p>对于80%的数据，n<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">≤5，其中有结果≥2000000的数据1个。</span></p><p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">余下数据满足n<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">≤10。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">[输出样例1]<br style="">2</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">[输出样例2]<br style="">0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=5</p><p>超限数据<span style="text-decoration: line-through;">从心所欲，不逾矩</span>（如上）</p>
</div>
</div>