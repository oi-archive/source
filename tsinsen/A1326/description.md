<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Answer的数学太差了，他决定恶补一番。<br/>
　　不过在学其他东西之前，他必须先精通加减乘除四则运算。<br/>
　　他想知道对于N个变量，每个变量只能用一次，且不能有前导符号，在可以使用括号的基础上，有多少种本质不同的运算方案？由于答案会很大，所以只需要输出模1000000007之后的答案。<br/>
　　两个方案本质相同即，无论如何改变这些变量的值，两种方案的结果不变(当然，要在表达式有意义的基础上)<br/>
　　例如:a/b/c和a/(b*c)的本质是相同的。<i></i></div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个正整数Test表示数据组数。<br/>
　　以下Test行，每行表示一个询问N,询问N个变量的本质不同的表达式方案。</div>
# 输出格式

<div class="pdcont">　　输出一个非负整数，表示方案数模1000000007后的值。</div>
# 样例输入

<div class="pddata">2<br/>
1<br/>
2</div>
# 样例输出

<div class="pddata">1<br/>
6</div>
# 样例说明

<div class="pdcont">　　对于N=2,有a+b,a-b,b-a,a*b,a/b,b/a六种方案。</div>
# 数据规模和约定

<div class="pdcont">　　对于30%的数据，满足1≤N≤50<br/>
　　对于100%的数据,满足1≤N≤2000,1≤Test≤2000</div>

</div>