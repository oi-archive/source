<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　对于一个n位的十进制数x（A<sub>n</sub>A<sub>n-1</sub>……A<sub>1</sub>），我们定义它的权重为：<br/>
　　F(x)=A<sub>n</sub>*2<sup>n-1</sup>+A<sub>n-1</sub>*2<sup>n-2</sup>+……+A<sub>1</sub>*2<sup>0</sup><br/>
　　现在，给你两个十进制数A和B，请计算出在闭区间[0, B]之中，有多少个数x的权重不大于A的权重，即F(x)&lt;=F(A)。由于答案可能很大，你只需要输出答案对1000000007（10<sup>9</sup> + 7）取模的结果即可。</div>
# 输入格式

<div class="pdcont">　　第一行一个正整数T，表示测例的个数。<br/>
　　随后T行，每行描述一个测例，包含两个非负整数A、B，之间用空格隔开。含义见问题描述。</div>
# 输出格式

<div class="pdcont">　　对于每个测例，单独输出一行”Case #t: ans”，其中t表示测例编号，从1开始递增，ans表示该组测例的答案（对1000000007取模后的结果）。</div>
# 样例输入

<div class="pddata">3<br/>
0 100<br/>
1 10<br/>
5 100</div>
# 样例输出

<div class="pddata">Case #1: 1<br/>
Case #2: 2<br/>
Case #3: 13</div>
# 样例说明

<div class="pdcont">　　对于Case #3，符合条件的数有0, 1, 2, 3, 4, 5, 10, 11, 12, 13, 20, 21, 100，共13个。<br/>
<br/>
　　//样例描述有修改，请注意！</div>
# 数据规模及约定

<div class="pdcont">　　对于20%的数据，A, B &lt;= 10<sup>9</sup>；<br/>
　　对于30%的数据，A, B &lt;= 10<sup>18</sup>；<br/>
<br/>
　　对于100%的数据，A,B &lt;= 10<sup>200</sup>，T&lt;=5。</div>

</div>