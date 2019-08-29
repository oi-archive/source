<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　通过代数基本定理，我们知道若计算重根，一个<i>n</i>次的多项式在复数域内<b>恰好有</b><b><i>n</i></b><b>个零点(</b><b>函数值为0</b><b>的点)</b>。现给定一个<b>整系数多项式</b>F[x]，它的<i>n</i>个零点恰好<b>都是有理数</b>（即可以写成两个整数相除的形式）；同时，若我们把它所有的<b>非零零点</b>（函数自变量不为0，函数值为0）去重，则可以得到<i>r</i>个<b>互不相同的非零零点</b>，其中第<i>i</i>个非零零点可以被表示成下式：sgn_i*q_i/p_i 。<br/>
　　式中 sgn_i  表示第i个零点的符号，p_i  和 q_i  为互质的两个正整数。<br/>
　　现在告诉你F[x]，要求你输出将它因式分解后的形式。</div>
# 输入格式

<div class="pdcont">　　输入只有一行，包含多项式F[x]。<br/>
　　多项式一定是如下的形式：<br/>
　　a_n x^n+a_(n-1) x^n-1+⋯a_1 x+a_0<br/>
　　次数一定为从高到低，其中a_i为整数，并且若a_i为0，则省略该项，若a_i为负数，则省略之前的加号，若 a_i  的绝对值为1且i不为0，则不输出1，并且保证a_n  不为0。<br/>
　　详见样例输入。</div>
# 输出格式

<div class="pdcont">　　输出一行，表示因式分解后的形式，格式如下：<br/>
　　a_n (x+u_1/v_1)^t_1 (x+u_2/v_2)^t_2…(x+u_s/v_s)^t_s<br/>
　　其中u，v互质，且v为正整数。<br/>
　　其中u_i/v_i从小到大排列，若 u_i/v_i=0 则该项为x^ti，若 u_i/v_i  为负数，则省略加号，若 v_i  为1，则省略/v_i。<br/>
　　若 t_i  为1则省略^ t_i。<br/>
　　若 a_n  为 ±1 则将 1 省略。<br/>
　　详见样例输出。</div>
# 样例输入

<div class="pddata">8x^7-258x^5+2112x^3-512x</div>
# 样例输出

<div class="pddata">8(x-4)^2(x-1/2)x(x+1/2)(x+4)^2</div>
# 样例输入

<div class="pddata">-x^2+2x-1</div>
# 样例输出

<div class="pddata">-(x-1)^2</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号<br/>
</td><td style="border:solid 1.0pt">多项式最高次数<br/>
</td><td valign="top" style="border:solid 1.0pt">互异零点数<br/>
</td><td style="border:solid 1.0pt">系数范围(绝对值)<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">≤ 10<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">≤ 100<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^6<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^7<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">12<br/>
</td><td valign="top" style="border:solid 1.0pt">12<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^16<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">35<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^24<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">39<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^68<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">46<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^104<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">80<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^12<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10^316<br/>
</td></tr></tbody></table><br/>
　　p_i,q_i  满足：<br/>
　　∏ p_i ≤10^6,∏ q_i≤10^6</div>

</div>