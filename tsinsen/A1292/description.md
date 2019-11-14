<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　<i>N</i> bombs are planted in a line, numbered from 0 to <i>N</i> sequentially. If we regard the line as an axis, the position of the <i>i</i>-th bomb can be characterized by a real number <i>P<sub>i</sub></i>, denoting its coordinate on the axis.<br/>
　　It has been found out that if the <i>i</i>-th bomb explodes, all other bombs not farther than <i>c</i>*<i>R<sub>i</sub></i> meters from it will also explode, where <i>R<sub>i</sub></i> is a real number related to the intrinsic properties of the bomb, which is probably not the same among all the bombs, and <i>c</i> is a real random variable evenly distributed in the range [<i>lower</i>, <i>upper</i>], immutable and applicable to all bombs.<br/>
　　Now please calculate the expected number of exploded bombs if, initially, the bomb number 0 is set off.</div>
# 输入格式

<div class="pdcont">　　The input contains multiple test cases.<br/>
　　For each test case:<br/>
　　The first line of the input contains three numbers, <i>N</i>, <i>lower</i> and <i>upper</i>.<br/>
　　The following two lines contain <i>N</i> integers each, which are all <i>P<sub>i</sub></i> and all <i>R<sub>i</sub></i>, respectively.<br/>
　　There are no empty lines between consecutive cases.</div>
# 输出格式

<div class="pdcont">　　For each test case, the output should contain exactly one line with one real number rounded to 2 decimal places, the expected number of exploded bombs.</div>
# 样例输入

<div class="pddata">5 1.0 3.0<br/>
1 3 5 7 9<br/>
1 1 1 1 1<br/>
5 1 11.0<br/>
0 2 8 22 1000000<br/>
1 2 1 10 1</div>
# 样例输出

<div class="pddata">3.00<br/>
2.80</div>
# Constraints

<div class="pdcont">　　For all test cases, 1 ≤ <i>N</i> ≤ 10^<sup>5</sup>, 0 &lt; <i>lower</i> &lt; <i>upper</i> ≤ 10^<sup>6</sup>, 0 ≤ <i>P<sub>i</sub></i> ≤ 10^<sup>8</sup>, 1 ≤ <i>R<sub>i</sub></i> ≤ 10^<sup>8</sup>, and the sum of the value <i>N</i> in all test cases will not exceed 2×10^<sup>5</sup>.</div>

</div>