<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Fred正在考虑在路易斯安那州找一块土地在上面建造他的房子。在调查过程中，他了解到路易斯安那州的陆地正以每年50平方英里的速度缩小，原因是密西西比河对陆地的侵蚀。由于Fred希望他的余生都能居住在这所房子里，所以他需要知道他的土地是否会被河水侵蚀。<br/>
　　Fred做了更多的研究后发现，正在损失的陆地呈现出一个半圆形的形状，这个半圆是以(0,0)为圆心的圆的X轴以上的部分，X轴以下的区域是河水，在第一年开始时这个半圆的面积是0。(如下图所示)<br/>
<img width="229" height="201" src="source/tsinsen/A1016/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9dDVHaGVlTjU=.do"/></div>
# 输入格式

<div class="pdcont">　　第一行是一个正整数表示接下来有多少组数据，以下的每一行代表一组数据，每组数据由两个浮点数组成，以空格隔开，分别代表Fred房子在平面内的坐标X和Y，单位是英里，其中Y&gt;=0。</div>
# 输出格式

<div class="pdcont">　　对于每一组输入数据，输出一个整数Z，代表Fred的房子会在第Z年中被河水侵蚀。如果在第Z年结束时Fred的房子正好在半圆的边界上，那么应该算作是在第Z+1年被侵蚀，返回Z+1。每个返回结果占一行。</div>
# 样例输入

<div class="pddata">2<br/>
1.0 1.0<br/>
25.0 0.0</div>
# 样例输出

<div class="pddata">1<br/>
20</div>

</div>