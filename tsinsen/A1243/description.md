<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　《超级马里奥兄弟》是任天堂于1985年出品的著名横版过关游戏，作为1983年游戏《马里奥兄弟》的续作在FC红白机上推出。在游戏《超级马里奥兄弟》中，玩家控制马里奥从库巴手上设法营救Peach公主。<br/>
　　今年是《超级马里奥兄弟》发行25周年了，任天堂推出了25周年纪念合集。lqp也想来凑热闹，他开发了一个小游戏，叫做“Mario填格子”。游戏是这样的，Boss Wario给出了一个3*3的小格子，在左上角填上了M，右下角填上了N。现在开始倒计时了，你必须给剩余的几个格子填上一些正整数，对于每个格子（格子里的数是X）满足：<br/>
　　1．如果它左边相邻有一个数Y，那么Y|X（表示Y整除X）。<br/>
　　2．如果它上面相邻有一个数Z，那么Z|X。<br/>
　　3．不存在和它填有相同数字的格子。<br/>
　　比如下面就是一个M=1, N=36的满足条件的填法：<br/>
<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt">2<br/>
</td><td style="border:solid 1.0pt">4<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3<br/>
</td><td style="border:solid 1.0pt">6<br/>
</td><td style="border:solid 1.0pt">12<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9<br/>
</td><td style="border:solid 1.0pt">18<br/>
</td><td style="border:solid 1.0pt">36<br/>
</td></tr></tbody></table></div>
# 输入格式

<div class="pdcont">　　输入包含若干行，以EOF结束。<br/>
　　每行包含两个正整数M和N，分别是左上角的数字和右下角的数字。</div>
# 输出格式

<div class="pdcont">　　如果Mario能够获胜，输出“Mario_wins!”，然后接下来三行输出任何一个方案。如果Mario不能够获胜，输出“ Wario_wins!”。每个数据输出一个空行。<br/>
　　（Special Judge不会判断你的输出格式。）</div>
# 样例输入

<div class="pddata">1 36<br/>
4 36</div>
# 样例输出

<div class="pddata">Mario_wins!<br/>
1 2 4<br/>
3 6 12<br/>
9 18 36<br/>
<br/>
Wario_wins!</div>
# 数据说明

<div class="pdcont">　　10%数据满足：1≤M, N≤9<br/>
　　30%数据满足：1≤M, N≤100<br/>
　　50%数据满足：1≤M, N≤100000<br/>
　　100%数据满足：最多10组测试数据，1≤M, N≤10<sup>17</sup><br/>
　　其中有10%数据N=M*p<sup>T</sup>。</div>

</div>