<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>右图，就是一个大小为6的三角形棋盘：<img src="/source/codevs/codevs-6054/img/aHR0cDovL3d3dy5nZGZ6b2ouY29tL3VwbG9hZC9mZXRjaF9pbWFnZS8xZmY1MzQzMjRiMTE0YTE2NzYzY2VlMmZiNTExZWNlMy5wbmc=.png"></span></p><p><br></p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>图1给出的是皇后攻击范围的示例——每个皇后有三个方向可以自由攻击。</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>图2给出的是在一个三角形棋盘上的不能互相攻击的4个皇后。</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>现在，你有一个三角形棋盘，棋盘上已经放置了几个互相不能攻击的皇后，请问棋盘上最多还能放多少个皇后，使得她们仍然不能互相攻击；并求出有多少种方案可以放这么多皇后。</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>在输出中输出这两个数。</p><p><span style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'><br></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>第一行一个数字N，代表棋盘的大小。</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>接下来N行，第i行有i个字符。表示棋盘第i行的状态，‘.’表示空，‘*’表示有皇后。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-size: 14px; background-color: rgb(255, 255, 255);">两行，每行一个数字，分别为在原来的棋盘上最多能放的皇后数量，和放置这么多皇后的方案种数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>2</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>.</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>..</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'><span style="font-family: sans-serif;"></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>1</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>1&lt;=N&lt;=13</span></p>
</div>
</div>