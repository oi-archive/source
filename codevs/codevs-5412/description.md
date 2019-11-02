<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">在外太空航行的飞船拍到了某种外星生命的图像。科学家在研究该图像时，把该图像分为n行m列, 共n*m个格子，每格给出了一个以整数表示的相似度的值。现在请你帮助统计该图像可以分成几部分？</span></p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">给定一个正整数的灵敏度值x, 如果某格与某相邻格子的相似度值的差值小于或等于x时，该格与该相邻格子属于同一个部件（所谓相邻，是指上、下、左、右之一）。如下图所示，当灵敏度值分别为10和5时，可以分为3个部件和5个部件。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">10 15 13 252 250 235</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">28 25 10 250 245 240</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">100 105 11 12 91 89</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">99 104 102 100 90 88</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;"><br></p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">10 15 13 252 250 235</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">28 25 10 250 245 240</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">100 105 11 12 91 89</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">99 104 102 100 90 88</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">输入文件live.in中有若干行：</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第一行有三个整数n、m和x,表示图像有n行m列,设定的灵敏度为x。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第二行起至第n+1行，每行有m个整数，互相间以一个空格分隔。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第k+1行的第j个整数，表示图像中第k行第j列的相似度值。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Segoe UI&#39;, &#39;Lucida Grande&#39;, Helvetica, Arial, &#39;Microsoft YaHei&#39;, FreeSans, Arimo, &#39;Droid Sans&#39;, &#39;wenquanyi micro hei&#39;, &#39;Hiragino Sans GB&#39;, &#39;Hiragino Sans GB W3&#39;, FontAwesome, sans-serif; font-size: 15px; line-height: 24px; background-color: rgba(255, 255, 255, 0.8);">输出文件live.out中只有一行，该行只有一个整数，表示可以划分出的部件数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">样例输入1：
4  6  10
10 15 13 252 250 235
28 25 10 250 245 240
100 105 11 12 91 89
99 104 102 100 90 88
样例输入2：
4   6   5
10 15 13 252 250 235
28 25 10 250 245 240
100 105 11 12 91 89
99 104 102 100 90 88</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">样例输出1：
3
样例输出2：
5</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">1≤n,m≤1000</span></p>
</div>
</div>