<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Vasya一直以来就有收集各种票的习惯<br/>
　　在收集了几千张火车票,公交票,地铁票之后,他已经厌倦了传统意义上对票据幸运与否的定义.他正在寻找新的视角来评价票据的幸运程度.他不能理解为什么人们只把所有票据分为幸运和不幸运两种,他认为所有的票据都是幸运的,只不过幸运程度不同罢了.<br/>
　　Vasya定义了一种幸运度 定义方式如下<br/>
　　每张票据由2*n位数字组成,所有数字由以下方式表示<br/>
<img src="source/tsinsen/A1444/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NTc3M2JtVDc=.do" width="792" height="155"/><br/>
　　这些如同电子钟上的一样的数字由七段线段组成,有的有颜色,有的没颜色.有颜色的表示了一个数字.Vasya把右边的n个数字迭在左边上,也就是第n+1个数字迭在第1个上,第n+2个数字迭在第2个上 …..<br/>
　　对于每一对迭在一起的数字, Vasya统计在两个数字中都有颜色的线段的条数,把n个条数加起来,得到幸运值.比如03的幸运值是4,2345的幸运值是6<br/>
　　现在给你一个2*n位的数字,请你求出最小的一个大于它的2*n位的数字,使其幸运值也大于它的幸运值.</div>
# 输入格式

<div class="pdcont">　　仅一行 一个2*n位的数字</div>
# 输出格式

<div class="pdcont">　　仅一行 一个2*n位的数字表示答案 无解输-1</div>
# 样例输入

<div class="pddata">13</div>
# 样例输出

<div class="pddata">20</div>
# 数据规模和约定

<div class="pdcont">　　1&lt;=n&lt;=100000</div>

</div>