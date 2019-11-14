<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出n组数据,每组数据包括x1,x2,x3,x4....xm,y。<br/>
　　要求求出f(x1,x2,x3,x4....,xm) = a1x1+a2x2+....amxm+B。<br/>
　　使得∑(Abs(f(x1,x2,x3....,xm)-y))<b>尽量小。</b></div>
# 输入格式

<div class="pdcont">　　第一行:n,m。<br/>
　　下面n行:每行前m个数表示x[],最后一个数表示y。</div>
# 输出格式

<div class="pdcont">　　前m个数a[]，<br/>
　　最后一个数B，<br/>
　　均保留3 位小数。</div>
# 样例输入

<div class="pddata">3 2<br/>
1 2 6<br/>
3 2 8<br/>
5 3 12</div>
# 样例输出

<div class="pddata">1.000 2.000 1.000</div>
# 数据规模和约定

<div class="pdcont">　　10% n == m且 n &lt;= 100<br/>
　　另外20% n == m+1且n &lt;= 100<br/>
　　另外 20% n &gt; m+1 且 n &lt;= 10<br/>
　　另外 50% n &gt; m+1 且 n &lt;= 100<br/>
　　x[],y为实数</div>
# 评分规则

<div class="pdcont">　　设你给出的sum = ∑(Abs(f(x1,x2,x3....,xm)-y)),标程给出的为ans<br/>
　　若sum &lt;= ans 你将获得10分.<br/>
　　否则你将获得10*(ans/sum)^3</div>

</div>