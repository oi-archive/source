<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont"><img width="609" height="350" src="source/tsinsen/A1185/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RFlRNmdhZ20=.do"/><br/>
　　在一个遥远的国度，一侧是风景秀美的湖泊，另一侧则是漫无边际的沙漠。该国的行政区划十分特殊，刚好构成一个N 行M 列的矩形，如上图所示，其中每个格子都代表一座城市，每座城市都有一个海拔高度。   为了使居民们都尽可能饮用到清澈的湖水，现在要在某些城市建造水利设施。水利设施有两种，分别为蓄水厂和输水站。蓄水厂的功能是利用水泵将湖泊中的水抽取到所在城市的蓄水池中。因此，只有与湖泊毗邻的第1 行的城市可以建造蓄水厂。而输水站的功能则是通过输水管线利用高度落差，将湖水从高处向低处输送。故一座城市能建造输水站的前提，是存在比它海拔更高且拥有公共边的相邻城市，已经建有水利设施。   由于第N 行的城市靠近沙漠，是该国的干旱区，所以要求其中的每座城市都建有水利设施。那么，这个要求能否满足呢？如果能，请计算最少建造几个蓄水厂；如果不能，求干旱区中不可能建有水利设施的城市数目。</div>
# 输入格式

<div class="pdcont">　　输入的每行中两个数之间用一个空格隔开。<br/>
<br/>
　　输入的第一行是两个正整数N 和M，表示矩形的规模。<br/>
<br/>
　　接下来N 行，每行M 个正整数，依次代表每座城市的海拔高度。</div>
# 输出格式

<div class="pdcont">　　输出两行。如果能满足要求，输出的第一行是整数1，第二行是一个整数，代表最少建造几个蓄水厂；如果不能满足要求，输出的第一行是整数0，第二行是一个整数，代表有几座干旱区中的城市不可能建有水利设施。</div>
# 样例输入

<div class="pddata">2 5<br/>
9 1 5 4 3<br/>
8 7 6 1 2</div>
# 样例输出

<div class="pddata">1<br/>
1</div>
# 样例输入

<div class="pddata">3 6<br/>
8 4 5 6 4 4<br/>
7 3 4 3 3 3<br/>
3 2 2 1 1 2</div>
# 样例输出

<div class="pddata">1<br/>
3</div>
# 样例1 说明

<div class="pdcont">　　只需要在海拔为9 的那座城市中建造蓄水厂，即可满足要求。</div>
# 样例2 说明

<div class="pdcont">　　上图中，在3 个粗线框出的城市中建造蓄水厂，可以满足要求。以这3 个蓄水厂为源头<br/>
　　在干旱区中建造的输水站分别用3 种颜色标出。当然，建造方法可能不唯一。</div>
# 数据规模和约定

<div class="pdcont">　　本题共有10 个测试数据，每个数据的范围如下表所示：<br/>
<img width="636" height="280" src="source/tsinsen/A1185/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZnFSdG5ScVQ=.do"/></div>

</div>