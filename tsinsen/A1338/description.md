<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　苦无(Kunai)是一种忍者使用的形状像刀的武器，忍者通过投掷苦无攻击对手。<br/>
　　现在有<i>N</i>名忍者聚集在一块<i>H</i>行<i>W</i>列的棋盘式的广场上。每个忍者都站在其所在方块的中心处，任何两个忍者都不在同一个方块上。每个忍者都拿着一个苦无，面朝上、下、左、右四个方向中的一个方向站着。在时刻0，所有忍者同时向其所朝向的方向投掷苦无。<br/>
　　每个苦无将会一直保持其初始的方向，并以单位速度飞行。如果某个时刻一个位置上多于一个的苦无，它们将会相撞并且消失。苦无特别小，可以看成质点。同时，由于忍者的移动速度特别快，他们不会被苦无击中。<br/>
　　在下面的例子中，我们用箭头来表示苦无，而箭头的方向即为苦无的方向。在这些图中，所有的苦无都会相撞后消失。<br/>
<img width="486" height="117" src="source/tsinsen/A1338/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9dGEyUTloOUI=.do"/><br/>
　　在下面的图中，两个粗线箭头表示的苦无不会相撞。其中在第二个和第三个图中，其中一个粗线表示的苦无会与细线表示的苦无相撞后消失，因此不会撞上另一个粗线表示的苦无。<br/>
<img width="488" height="117" src="source/tsinsen/A1338/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9cWY4YnlCYWI=.do"/><br/>
　　你的任务是计算经过足够长的时间之后，在这个<i>W</i> × <i>H</i>的广场中有多少格子被苦无经过。</div>
# 数据规模和约定

<div class="pdcont">　　1 ≤ <i>N</i> ≤ 100,000                              忍者数；<br/>
　　1 ≤ <i>W</i> ≤ 1,000,000,000                   列数；<br/>
　　1 ≤ <i>H</i> ≤ 1,000,000,000                   行数；<br/>
　　1 ≤ <i>X<sub>i</sub></i> ≤ <i>W</i>，1 ≤ <i>Y<sub>i</sub></i> ≤ <i>H</i>                  坐标范围。<br/>
<br/>
　　在10%的数据中，<i>N</i> ≤ 1000, <i>W</i> ≤ 1000, <i>H</i> ≤ 1000。<br/>
　　在40%的数据中，<i>N</i> ≤ 1000。</div>
# 输入格式

<div class="pdcont">　　从标准输入读入数据。<br/>
　　第一行包含两个被空格隔开的整数<i>W</i>, <i>H</i>，表示广场的尺寸为<i>W</i>列<i>H</i>行。<br/>
　　第二行包含一个整数<i>N</i>，表示忍者的数量。<br/>
　　接下来<i>N</i>行中，第<i>i</i>行有三个以空格分隔的整数<i>X<sub>i</sub></i>, <i>Y<sub>i</sub></i>, <i>D<sub>i</sub></i>, 表示第<i>i</i>个忍者处在从左往右的<i>X<sub>i</sub></i>列、从上往下的第<i>Y<sub>i</sub></i>行，任何两个忍者不在同一个位置。第<i>i</i>个忍者面向的方向由<i>D<sub>i</sub></i>表示，分别为：<br/>
　　   <i>D<sub>i</sub></i> = 0，表示忍者向右；<br/>
　　   <i>D<sub>i</sub></i> = 1，表示忍者向上；<br/>
　　   <i>D<sub>i</sub></i> = 2，表示忍者向左；<br/>
　　   <i>D<sub>i</sub></i> = 3，表示忍者向下。</div>
# 输出格式

<div class="pdcont">　　输出到标准输出。<br/>
　　输出一个整数，表示经过足够长的时间之后，在这个<i>W</i> × <i>H</i>的广场中被苦无经过的格子数量。</div>
# 样例输入

<div class="pddata">5 4<br/>
5<br/>
3 3 2<br/>
3 2 0<br/>
4 2 2<br/>
5 4 1<br/>
1 1 3</div>
# 样例输出

<div class="pddata">11</div>
# 样例说明

<div class="pdcont">　　在时刻0，苦无的情况如下图所示<br/>
<img width="146" height="117" src="source/tsinsen/A1338/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZUFZVHJuZ2c=.do"/><br/>
　　在下面的描述中，忍者<i>i</i>投掷的苦无将用苦无<i>i</i>表示。<br/>
　　在时刻0.5，苦无2和苦无3相撞后消失。<br/>
　　下图为时刻1的情况，加深的格子表示已经被苦无经过。<br/>
<img width="146" height="117" src="source/tsinsen/A1338/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OEY4dDhCZjc=.do"/><br/>
　　在时刻2，苦无1和苦无5相撞后消失，此时的广场如下图所示。<br/>
<img width="146" height="117" src="source/tsinsen/A1338/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9WU4yZ2R0RVQ=.do"/><br/>
　　之后没有苦无相撞。再经过足够时间后的广场如下图所示。<br/>
<img width="146" height="117" src="source/tsinsen/A1338/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9UkpiaG01blQ=.do"/><br/>
　　共有11个格子被苦无经过，因此输出11。</div>
# 样例输入

<div class="pddata">7 6<br/>
12<br/>
3 2 3<br/>
6 3 2<br/>
7 1 3<br/>
1 5 0<br/>
3 6 1<br/>
6 6 1<br/>
4 5 2<br/>
1 3 0<br/>
6 5 2<br/>
5 1 2<br/>
6 4 3<br/>
4 1 3</div>
# 样例输出

<div class="pddata">29</div>

</div>