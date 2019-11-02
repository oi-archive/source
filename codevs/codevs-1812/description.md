<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在Dukeswood这块土地上生活着一个富有的农庄主和他的几个孩子。在他临终时，他想把他的土地分给他的孩子。他有许多农场，每个农场都是一块矩形土地。他在农场地图上划上一些直线将矩形分成若干块。当他划直线时，他总是从矩形边界上的某一点划到另一个矩形边界上的点，这条线的结束点将成为下一条线的起始点。他划线时从不会让任三线共点。例如下图是某一种划分结果。</p>
<p> <img height="249" src="../../../media/image/1812.png" width="357"></p>
<p> </p>
<p> </p>
<p>划分的起始点和结束点均以五角星标记。当他完成划分后，他想要数一下划出的土地的块数以确保每个孩子都有一块地。例如，上图中土地被划分成18块。然而这个庄主由于年迈常会数错，因而他寻求你的帮助。</p>
<p>请写一个程序，输入原来的土地尺寸及线段的位置，输出划分出的土地块数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入地图的宽度w(1&lt;=w&lt;=100)和高度h(1&lt;=h&lt;=100)，均为整数。</p>
<p>第二行输入线段数L(1&lt;=L&lt;=15)。</p>
<p>以下L+1行每行一个整数坐标(Xi,Yi)，庄主划的线段为(Xi,Yi)-(Xi+1,Yi+1)，i=1,2,…,L。当然(Xi,Yi)必定在矩形的边界上。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">对于给定的输入，输出一行仅含一个数，即划分出的土地块数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>19 12</p>
<p>8</p>
<p>2 0</p>
<p>6 12</p>
<p>11 0</p>
<p>19 9</p>
<p>17 12</p>
<p>0 7</p>
<p>15 0</p>
<p>11 12</p>
<p>0 10<strong></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>