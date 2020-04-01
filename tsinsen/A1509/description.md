<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　我们有N张纸牌，每张牌都有数字和颜色两个属性。今天我心情不错，想把这N张牌排成一行，使得相邻的两个要么颜色相同要么数字相同。数字在0到9之间，颜色有红黄蓝三种（用012来表示）。想让你求出方案数。</div>
# 输入格式

<div class="pdcont">　　第一行输入N，表示有N张纸牌。<br/>
<br/>
　　接下来N行，每行两个数字分别表示第i张牌的颜色和数字。</div>
# 输出格式

<div class="pdcont">　　一行输出答案，对2^32取模。</div>
# 样例输入

<div class="pddata">Sample Input 1:<br/>
3<br/>
0 0<br/>
0 0<br/>
0 0<br/>
<br/>
Sample Input 2:<br/>
3<br/>
0 1<br/>
0 2<br/>
1 2</div>
# 样例输出

<div class="pddata">Sample Output 1:<br/>
6<br/>
Sample Output 2:<br/>
2</div>
# 数据规模和约定

<div class="pdcont">　　10%的数据:n&lt;=10<br/>
　　另有10%的数据:n&lt;=20<br/>
　　另有30%的数据:n&lt;=30，最多只会有2种颜色，且不会有3张牌的数字和颜色都一样。<br/>
　　另有50%的数据:n&lt;=30，最多只会有3种颜色，且不会有4张牌的数字和颜色都一样。</div>

</div>