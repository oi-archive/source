<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　跳跳棋是在一条数轴上进行的。棋子只能摆在整点上。每个点不能摆超过一个棋子。<br/>
　　我们用跳跳棋来做一个简单的游戏：棋盘上有3颗棋子，分别在a，b，c这三个位置。我们要通过最少的跳动把他们的位置移动成x，y，z。（棋子是没有区别的）<br/>
　　跳动的规则很简单，任意选一颗棋子，对一颗中轴棋子跳动。跳动后两颗棋子距离不变。一次只允许跳过1颗棋子。<br/>
<img width="342" height="92" src="source/tsinsen/A1229/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OTVxNk5UeTQ=.do"/><br/>
　　写一个程序，首先判断是否可以完成任务。如果可以，输出最少需要的跳动次数。</div>
# 输入格式

<div class="pdcont">　　第一行包含三个整数，表示当前棋子的位置a b c。（互不相同）<br/>
　　第二行包含三个整数，表示目标位置x y z。（互不相同）</div>
# 输出格式

<div class="pdcont">　　如果无解，输出一行NO。<br/>
　　如果可以到达，第一行输出YES，第二行输出最少步数。</div>
# 样例输入

<div class="pddata">1 2 3<br/>
0 3 5</div>
# 样例输出

<div class="pddata">YES<br/>
2</div>
# 数据规模和约定

<div class="pdcont">　　20% 输入整数的绝对值均不超过10<br/>
　　40% 输入整数的绝对值均不超过10000<br/>
　　100% 绝对值不超过10^9</div>

</div>