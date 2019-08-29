<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出一个多项式，求出它的k阶导数。</div>
# 输入格式

<div class="pdcont">　　第一行为一个整数k，表示要求多项式的k阶导数。<br/>
　　第二行为一个整数n，表示要求导的多项式含有n项。<br/>
　　接下来输入多项式的各个非零项，每一项占一行，含两个整数a、b，表示多项式含有a*x^b这一项，其中b&gt;=0，a不为0。<br/>
　　n,k&lt;=100，结果中的所有系数不会超过int范围。</div>
# 输出格式

<div class="pdcont">　　按照书写习惯输出多项式，具体格式请严格参照样例。</div>
# 样例输入

<div class="pddata">1<br/>
4<br/>
-3 4<br/>
4 2<br/>
-2 1<br/>
7 0</div>
# 样例输出

<div class="pddata">f&#39;(x)=-12*x^3+8*x-2</div>
# 样例输入

<div class="pddata">3<br/>
3<br/>
1 10<br/>
2 50<br/>
-3 30</div>
# 样例输出

<div class="pddata">f&#39;&#39;&#39;(x)=720*x^7+235200*x^47-73080*x^27</div>

</div>