<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们憨厚的USACO 主人公农夫约翰(Farmer John)以无法想象的运气,在他生日那天收<br>到了一份特别的礼物：一张“幸运爱尔兰”（一种彩票）。结果这张彩票让他获得了这次比<br>赛唯一的奖品——坐落于爱尔兰郊外的一座梦幻般的城堡！<br>喜欢吹嘘的农夫约翰立刻回到有着吹嘘传统的威斯康辛老家开始吹嘘了, 农夫约翰想<br>要告诉他的奶牛们关于他城堡的一切。他需要做一些吹嘘前的准备工作：比如说知道城堡<br>有多少个房间，每个房间有多大。另外，农夫约翰想要把一面单独的墙（指两个单位间的<br>墙）拆掉以形成一个更大的房间。你的工作就是帮农夫约翰做以上的准备，算出房间数与<br>房间的大小。<br>城堡的平面图被划分成M*N(1 &lt;=M,N&lt;=50）个正方形的单位，一个这样的单位可以有<br>0 到4 面墙环绕。城堡周围一定有外墙环绕以遮风挡雨。（就是说平面图的四周一定是墙。）<br># =墙壁-,| = 没有墙壁-&gt; =指向一面墙，这面墙推掉的话我们就有一间最大的新房间。<br>友情提示，这个城堡的平面图是7×4 个单位的。一个“房间”的是平面图中一个由“#”、<br>“-”、“|”围成的格子（就是图里面的那一个个的格子）。比如说这个样例就有5 个房间。（大<br>小分别为9、7、3、1、8 个单位（排名不分先后））<br>移去箭头所指的那面墙，可以使2 个房间合为一个新房间，且比移去其他墙所形成的<br>房间都大。<br>城堡保证至少有2 个房间，而且一定有一面墙可以被移走。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个整数：M 和N 城堡的平面图用一个由数字组成的矩阵表示，一个数字表<br>示一个单位，矩阵有N 行M 列。输入与样例的图一致。<br>每一个单位的数字告诉我们这个单位的东西南北是否有墙存在。每个数字是由以下四<br>个整数的某个或某几个或一个都没有加起来的。<br>1: 在西面有墙<br>2: 在北面有墙<br>4: 在东面有墙<br>8: 在南面有墙</p>
<p>城堡内部的墙会被规定两次。比如说（1，1）南面的墙，亦会被标记为（2，1）北面<br>的墙。<br><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包含如下4 行:<br />第1 行: 城堡的房间数目。<br />第2 行: 最大的房间的大小<br />第3 行: 移除一面墙能得到的最大的房间的大小<br />第4 行: 移除哪面墙可以得到面积最大的新房间。<br />选择最佳的墙来推倒。有多解时选最靠西的，仍然有多解时选最靠南的。同一格子北<br />边的墙比东边的墙更优先。<br />用该墙的南邻单位的北墙或西邻单位的东墙来表示这面墙，方法是输出邻近单位的行<br />数、列数和墙的方位（"N"（北）或者"E"（东）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 4<br>11 6 11 6 3 10 6<br>7 9 6 13 5 15 5<br>1 10 12 7 13 7 5<br>13 11 10 8 10 12 13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p><span style="">9</span></p>
<p><span style="">16</span></p>
<p>4　1 E</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 &lt;=M,N&lt;=50</p>
</div>
</div>