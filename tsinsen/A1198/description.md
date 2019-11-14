<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　帅帅经常跟同学玩一个矩阵取数游戏：对于一个给定的<i>n</i>*<i>m</i>的矩阵，矩阵中的每个元素<i>a<sub>ij</sub></i>均为非负整数。游戏规则如下：<br/>
　　1.        每次取数时须从每行各取走一个元素，共<i>n</i>个。<i>m</i>次后取完矩阵所有元素；<br/>
　　2.        每次取走的各个元素只能是该元素所在行的行首或行尾；<br/>
　　3.        每次取数都有一个得分值，为每行取数的得分之和，<b>每行取数的得分</b><b> = </b><b>被取走的元素值</b><b>*2<i><sup>i</sup></i></b>，其中<i>i</i>表示第<i>i</i>次取数（从1开始编号）；<br/>
　　4.        游戏结束总得分为<i>m</i>次取数得分之和。<br/>
　　帅帅想请你帮忙写一个程序，对于任意矩阵，可以求出取数后的最大得分。</div>
# 输入格式

<div class="pdcont">　　输入包括<i>n</i>+1行：<br/>
　　第1行为两个用空格隔开的整数<i>n</i>和<i>m</i>。<br/>
　　第2~<i>n</i>+1行为<i>n</i>*<i>m</i>矩阵，其中每行有<i>m</i>个用单个空格隔开的非负整数。</div>
# 输出格式

<div class="pdcont">　　输出包含1行，为一个整数，即输入矩阵取数后的最大得分。</div>
# 样例输入

<div class="pddata">2 3<br/>
1 2 3<br/>
3 4 2</div>
# 样例输出

<div class="pddata">82</div>
# 样例输入

<div class="pddata">1 4<br/>
4 5 0 5</div>
# 样例输出

<div class="pddata">122</div>
# 样例输入

<div class="pddata">2 10<br/>
96 56 54 46 86 12 23 88 80 43<br/>
16 95 18 29 30 53 88 83 64 67</div>
# 样例输出

<div class="pddata">316994</div>
# 数据规模和约定

<div class="pdcont">　　60%的数据满足：1&lt;=<i>n</i>, <i>m</i>&lt;=30, 答案不超过10<sup>16</sup><br/>
　　100%的数据满足：1&lt;=<i>n</i>, <i>m</i>&lt;=80, 0&lt;=<i>a<sub>ij</sub></i>&lt;=1000。</div>

</div>