<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　丁丁最近沉迷于一个数字游戏之中。这个游戏看似简单，但丁丁在研究了许多天之后却发觉原来在简单的规则下想要赢得这个游戏并不那么容易。游戏 是这样的，在你面前有一圈整数（一共n个），你要按顺序将其分为m个部分，各部分内的数字相加，相加所得的m个结果对10取模后再相乘，最终得到一个数 k。游戏的要求是使你所得的k最大或者最小。<br/>
　　例如，对于下面这圈数字（n=4，m=2）：<br/>
<img width="191" height="197" src="source/tsinsen/A1144/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZDlGYXRtRjM=.do"/><br/>
<img src="source/tsinsen/A1144/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9THJBZ1Q5cTY=.do"/><br/>
　　当要求最小值时，((2-1)  mod 10)×((4+3) mod 10)=1×7=7，要求最大值时，为((2+4+3) mod 10)×(-1 mod  10)=9×9=81。特别值得注意的是，无论是负数还是正数，对10取模的结果均为非负值(比如-12%10=8，相当于-12%10＋10）。<br/>
　　丁丁请你编写程序帮他赢得这个游戏。</div>
# 输入格式

<div class="pdcont">　　输入文件第一行有用空格分开的两个整数，n和m。以下n行每行有个整数，其绝对值不大于104，按顺序给出圈中的数字，首尾相接。</div>
# 输出格式

<div class="pdcont">　　输出文件有两行，各包含一个非负整数。第一行是你程序得到的最小值，第二行是最大值。</div>
# 样例输入

<div class="pddata">4 2<br/>
4<br/>
3<br/>
-1<br/>
2</div>
# 样例输出

<div class="pddata">7<br/>
81</div>
# 数据规模和约定

<div class="pdcont">　　1≤n≤50<br/>
　　1≤m≤9</div>

</div>