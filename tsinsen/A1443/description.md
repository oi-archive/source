<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　我们定义UAE (<i>unambiguous arithmetic expression</i>) 为<br/>
<br/>
　　1.       所有的自然数是UAE,有前导零的自然数(比如0000,0010)也是UAE<br/>
　　2.       如果X和Y是UAE, 那么”(X)+(Y)”,”(X)-(Y)”,”(X)*(Y)”,”(X)/(Y)”也是UAE<br/>
　　3.       如果X 是UAE, 那么”-(X)”和”+(X)”是UAE<br/>
<br/>
　　现在给你一个只包含’0’-‘9’和’+’,’-’,’*’,’/’的字符串<br/>
　　让你计算有多少种不同的UAE,满足去掉了括号符号后就变成了输入中的串<br/>
　　答案Mod 1000003输出</div>
# 输入格式

<div class="pdcont">　　仅一行 一个只包含’0’-‘9’和’+’,’-’,’*’,’/’的字符串</div>
# 输出格式

<div class="pdcont">　　仅一行 一个整型表示答案如果不存在任何一种UAE满足条件 输出0</div>
# 样例输入

<div class="pddata">03+-30+40</div>
# 样例输出

<div class="pddata">3</div>
# 数据规模和约定

<div class="pdcont">　　串长&lt;=2000</div>

</div>