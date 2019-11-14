<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　最近FJ为他的奶牛们开设了数学分析课，FJ知道若要学好这门课，必须有一个好的三角函数基本功。所以他准备和奶牛们做一个“Sine之舞”的游戏，寓教于乐，提高奶牛们的计算能力。<br/>
　　不妨设<br/>
　　An=sin(1–sin(2+sin(3–sin(4+...sin(n))...)<br/>
　　Sn=(...(A1+n)A2+n-1)A3+...+2)An+1<br/>
　　FJ想让奶牛们计算Sn的值，请你帮助FJ打印出Sn的完整表达式，以方便奶牛们做题。</div>
# 输入格式

<div class="pdcont">　　仅有一个数：N&lt;201。</div>
# 输出格式

<div class="pdcont">　　请输出相应的表达式Sn，以一个换行符结束。输出中不得含有多余的空格或换行、回车符。</div>
# 样例输入

<div class="pddata">3</div>
# 样例输出

<div class="pddata">((sin(1)+3)sin(1–sin(2))+2)sin(1–sin(2+sin(3)))+1</div>

</div>