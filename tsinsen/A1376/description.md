<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　求∑∑((n mod i)*(m mod j))其中1&lt;=i&lt;=n,1&lt;=j&lt;=m,i≠j。</div>
# 输入格式

<div class="pdcont">　　第一行两个数n,m。</div>
# 输出格式

<div class="pdcont">　　一个整数表示答案mod 19940417的值</div>
# 样例输入

<div class="pddata">3 4</div>
# 样例输出

<div class="pddata">1</div>
# 样例说明

<div class="pdcont">　　答案为(3 mod 1)*(4 mod 2)+(3 mod 1) * (4 mod 3)+(3 mod 1) * (4 mod 4) + (3 mod 2) * (4 mod 1) + (3 mod 2) * (4 mod 3) + (3 mod 2) * (4 mod 4) + (3 mod 3) * (4 mod 1) + (3 mod 3) * (4 mod 2) + (3 mod 3) * (4 mod 4) = 1</div>
# 数据规模和约定

<div class="pdcont">　　对于10%的数据n,m&lt;=1000；<br/>
　　对于30%的数据 n,m&lt;=1000000；<br/>
　　另有30%的数据n&lt;=100，m&lt;=10<sup>9</sup>；<br/>
　　对于100%的数据n,m&lt;=10<sup>9</sup>。</div>

</div>