<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　多米诺骨牌有许多种玩法。其中一个有趣的事实是，将一个标准国际象棋棋盘 (8 × 8)去掉两个格子，如果这两个格子异色，则总可以用1 × 2的多米诺骨牌填满，否则不能填满。<br/>
　　Petya已经厌倦了多米诺骨牌游戏。所以他准备了一个棋盘（不一定8 × 8），去掉了一些格子，然后尝试用trimino填满。trimino是一种1 × 3（或3 × 1，因为trimino可以随意旋转）的长方形，两端的两个格子是白色的，中间的格子是黑色的。trimino被允许填在棋盘的某个位置，只有当trimino的三个格子的颜色与棋盘上对应位置的颜色相同，黑色格子对应棋盘上的黑色格子，白色格子对应棋盘上的白色格子。trimino不能伸出棋盘，也不能互相重叠。棋盘上每个未去除的格子都必须被trimino覆盖。<br/>
　　请帮助Petya判断能否用trimino填满他的棋盘并输出一种方案。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个正整数n和m，表示棋盘的大小。接下来n行，每行m个字符，用于表示棋盘。如果某个位置的字符是&#34;.&#34;，就表示这个位置的格子已经被去掉了。字符&#34;w&#34;表示白色格子，&#34;b&#34;表示黑色格子。保证在填上去掉的格子后棋盘是正确的（黑白格子相间），尽管大小可能不标准。</div>
# 输出格式

<div class="pdcont">　　如果存在某种填充方案，则在第一行输出&#34;YES&#34;（不包含引号），然后输出填充方案。填充方案必须包括n行，每行m个字符。去除的格子，和输入一样，用&#34;.&#34;表示。对trimino则用&#34;a&#34;, &#34;b&#34;, &#34;c&#34;, &#34;d&#34;四个字符表示，一个trimino的三个格子必须用同一字符表示。如果两个trimino相邻于一条边，则它们必须用不同的字符表示。不相邻于一条边的两个trimino可以用同一字符表示（参见样例）。<br/>
　　如果有多种填充方案，输出任意一种方案即可。如果不能用trimino填满这个棋盘，或者填充方案不能用&#34;a&#34;, &#34;b&#34;, &#34;c&#34;, &#34;d&#34;四个字符表示出来，则在第一行输出&#34;NO&#34;（不包含引号）。</div>
# 样例输入

<div class="pddata">样例输入一：<br/>
6 10<br/>
.w.wbw.wbw<br/>
wbwbw.w.w.<br/>
bw.wbwbwbw<br/>
w.wbw.wbwb<br/>
...wbw.w.w<br/>
..wbw.wbw.<br/>
样例输入二：<br/>
2 2<br/>
wb<br/>
bw</div>
# 样例输出

<div class="pddata">样例输出一：<br/>
YES<br/>
.a.aaa.ccc<br/>
baccc.c.a.<br/>
ba.dddcbab<br/>
b.aaa.cbab<br/>
...bbb.b.b<br/>
..ccc.ddd.<br/>
样例输出二：<br/>
NO</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">数据组数</td><td style="border:solid 1.0pt">输入数据或输入数据规模</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1</td><td style="border:solid 1.0pt">8 10<br/>
.....w....<br/>
....wbwbw.<br/>
.wbwbw.wbw<br/>
wbw.w...w.<br/>
.wbw...wb.<br/>
..wbw.wbw.<br/>
...wbwbw..<br/>
......w...<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2</td><td style="border:solid 1.0pt">10 11<br/>
...w.w.wbw.<br/>
wbwbwbwbw..<br/>
.w.wbw.wbw.<br/>
.b..w.wbw.w<br/>
.w.wbw.wbwb<br/>
wbw.wbw.w.w<br/>
.wbw.wbwbw.<br/>
wbw.wbw.wbw<br/>
.........wb<br/>
..........w<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3~20</td><td style="border:solid 1.0pt">1 ≤ n, m ≤ 20</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">21~30</td><td style="border:solid 1.0pt">1 ≤ n, m ≤ 100</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">31~50</td><td style="border:solid 1.0pt">1 ≤ n, m ≤ 1000</td></tr></tbody></table></div>

</div>