<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">球球大作战是一个烧脑的手游，一个球球叫咕噜咕噜(细节不用阐述)……</p><p style="">一天，咕噜咕噜被邪恶的Skyzcy抓走了……</p><p style="">Skyzcy知道咕噜咕噜有法术，所以把咕噜咕噜关在一个n*m的迷宫里，并在迷宫的某些地方设置了一些刺球(要知道球球是不能经过刺球的)，但这些刺球可以通过棒棒糖(球球世界通用货币)来解锁，并消除刺球，棒棒糖与刺球一一对应，即一种棒棒糖只能解锁一种刺球(比如a棒棒糖只能解锁A刺球)，棒棒糖藏在迷宫另外的某些地方，也有可能就在刺球前。一开始咕噜咕噜被关在(x1,y1)的位置，离开迷宫的出口在(x2,y2)的位置。咕噜咕噜每分钟只能从一个坐标走到相邻四个坐标中的其中一个(分身术也无能为力)。Skyzcy每t分钟回迷宫视察一次，若发现咕噜咕噜不在(x1,y1)便把他拎回去。经过无数次尝试，咕噜咕噜已摸索出迷宫的地图。现在请你帮咕噜咕噜计算能否成功逃亡。</p><p style="">若在Skyzcy下次视察之前走到出口(x2,y2)就算成功，如果Skyzcy回来的时候刚好走到出口(迎面撞上可是非常尴尬的)或还未到出口都算失败。 </p><p><br style=""></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每个测试点有一组测试数据，第一行有三个整数n,m,t(2&lt;=n,m&lt;=50,t&gt;=0)。接下来的n行m列为咕噜咕噜手绘的地图： </p><p>. 代表空白区域，即咕噜咕噜可以走的地方 </p><p>* 代表迷宫的墙，即咕噜咕噜永远无法走的地方 </p><p>@ 代表咕噜咕噜的起始位置 </p><p>^ 代表迷宫的出口 </p><p>A-J 代表刺球,对应的棒棒糖分别为a-j </p><p>a-j 代表棒棒糖，对应的刺球分别为A-J </p><p><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>针对每个测试点，如果可以成功离开迷宫，请输出需要多少分钟才能离开，如果不能则输出-1。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 17</p><p>@A.B.</p><p>a*.*.</p><p>*..*^</p><p>c..b*</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2&lt;=n,m&lt;=50,t&gt;=0</p>
</div>
</div>