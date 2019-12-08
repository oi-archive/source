<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>        IOI2002的颁奖典礼将在YONG-IN Hall隆重举行。人们在经历了充满梦幻的世界杯之后变得更加富于情趣。为了使颁奖典礼更具魅力，有人建议在YONG-IN Hall中搭建一个I字型的颁奖台，以此代表信息学Informatics。考虑到比赛的赞助商们可能要在YONG-IN Hall中摆设了许多展示台，他们可能不愿意移动展示台的位置。你作为IOI2002的金牌得主自然地成为了他们求助的对象。</p>
<p>       YONG-IN Hall是一个矩形的网格区域。每个赞助商的展示台都占据了若干个单位网格。I型颁奖台将正向搭建，且平行于YONG-IN Hall的边缘。I型颁奖台是由三个矩形相接叠成的，其中上方和下方的矩形的两侧必须都超出中间的矩形，否则将被误解成T, L, J等字母。</p>
<p> <span style=""> </span></p>
<p>       希望你编程寻找面积最大的I型颁奖台，使其不覆盖任何展示台。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数n, m(1&lt;=n,m&lt;=200)，分别表示YONG-IN Hall的矩形网格区域的行数和列数。以下n行每行包含m个数字，非0即1，每个数字描述一个单位网格，1表示该单位网格存在展示台，0表示该单位网格不存在展示台。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个正整数，表示最大的I型颁奖台的面积。如果不存在合法的I型颁奖台，则输出0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 8</p>
<p>1 1 1 1 1 0 0 1</p>
<p>1 0 0 0 0 1 1 1</p>
<p>1 0 0 0 0 0 1 1</p>
<p>1 0 1 0 1 0 1 0</p>
<p>1 0 0 0 0 0 0 1</p>
<p>1 1 0 0 0 1 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>