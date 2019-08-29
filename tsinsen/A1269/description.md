<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在一个圆上均匀分布p*q个点{A<sub>1</sub>，A<sub>2</sub>，A<sub>3</sub>…A<sub>p*q</sub>}，Ai与Aj的距离为min{abs(i-j)，p*q-abs(i-j)}，在上面选任意个点(可以选0个)，如果选择的点中存在两个点距离为p或q，就会发生排斥反应，求不发生排斥反应的方案总数。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个整数，分别表示p和q</div>
# 输出格式

<div class="pdcont">　　输出一个整数，表示方案总数，由于这个题答案可能很大，只要输出答案mod 19921107</div>
# 样例输入

<div class="pddata">1 6</div>
# 样例输出

<div class="pddata">18</div>
# 数据说明

<div class="pdcont">　　对于5%的数据，p=1，q&lt;=10<sup>6</sup><br/>
　　对于15%的数据，p=1，q&lt;=10<sup>9</sup><br/>
　　对于100%的数据，p&lt;=10，q&lt;=10<sup>9</sup>，p和q互质<br/>
　　对于100%的数据，时间限制为2s。</div>

</div>