<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小T的城市刚刚开始推行BRT（Bus Rapid Transit），其实，就是一种公交车。<br/>
　　BRT有N个站台，分别编号为1到N，按照列车通过的顺序递增排列。在列车到站时，会有一些乘客上车，也会有一些乘客下车。<br/>
　　由于BRT内空间狭小，乘客完全无法走动，在车上只有靠近车门的乘客才能够下车。和大部分公交车一样，BRT有2个车门——前门和后门。每一个上车的乘客可以选择从前门或者后门上车。<br/>
　　现在有M个乘客，编号为1到M，每个人都有各自的起点和终点，现在，需要聪明的你来安排一种上下车的方案，使得每个乘客都能够在各自的终点下车。</div>
# 输入格式

<div class="pdcont">　　第一行是两个整数N,M。下面依次有M行，每行有两个整数，表示一个乘客的起点和终点。</div>
# 输出格式

<div class="pdcont">　　输出你的方案：<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1 X<br/>
</td><td valign="top" style="border:solid 1.0pt">编号为X的乘客从前门上车<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2 X<br/>
</td><td valign="top" style="border:solid 1.0pt">编号为X的乘客从后门上车<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3 X<br/>
</td><td valign="top" style="border:solid 1.0pt">编号为X的乘客下车<br/>
</td></tr></tbody></table><br/>
输出包括2M行，每行一种操作</div>
# 样例输入

<div class="pddata">5 7<br/>
1 3<br/>
1 2<br/>
2 3<br/>
2 4<br/>
4 5<br/>
3 5<br/>
3 5</div>
# 样例输出

<div class="pddata">1 1<br/>
1 2<br/>
3 2<br/>
2 4<br/>
1 3<br/>
3 3<br/>
3 1<br/>
1 7<br/>
1 6<br/>
3 4<br/>
1 5<br/>
3 7<br/>
3 6<br/>
3 5</div>
# 数据规模和约定

<div class="pdcont">对于100%的数据满足1≤n,m≤200</div>

</div>