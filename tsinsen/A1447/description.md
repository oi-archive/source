<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　幸运数字是那些仅由4和7构成的数字，比如477，44，777是幸运数字，而789，457，123不是幸运数字。<br/>
　　有一天Petya得到了一个长度为N的非负整数序列A，其中A[i]表示该序列的第i个元素。他想从整个序列中选出两个互不相交的子段A[L1,R1], A[L2,R2](1&lt;=L1&lt;=R1&lt;L2&lt;=R2&lt;=n)，使得不存在某个幸运数字既在A[L1,R1]出现，又在A[L2,R2]出现。Petya想知道他有多少种选择方案，你能帮帮他吗？<br/>
　　Petya保证A序列中幸运数字的总出现次数不会超过1000次。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个正整数n，表示A序列的长度。<br/>
　　第二行包含n个整数，第i个整数表示A[i]。</div>
# 输出格式

<div class="pdcont">　　输出一行表示总的方案个数。</div>
# 样例输入

<div class="pddata">4<br/>
1 4 2 4</div>
# 样例输出

<div class="pddata">9</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号</td><td style="border:solid 1.0pt">约定</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1</td><td style="border:solid 1.0pt"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">n = 5</td><td style="border:solid 1.0pt">A = {7 9 2 8 7} </td></tr></tbody></table></td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2</td><td style="border:solid 1.0pt"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">n = 5</td><td style="border:solid 1.0pt">A = {9 4 7 4 7}</td></tr></tbody></table></td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3~6</td><td style="border:solid 1.0pt">n &lt;= 100</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7~12</td><td style="border:solid 1.0pt">n &lt;= 10000，幸运数字的总出现次数不超过200</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">13~20</td><td style="border:solid 1.0pt">n &lt;= 100000，幸运数字的总出现次数不超过1000</td></tr></tbody></table><br/>
　　对于100%的数据，保证1&lt;=A[i]&lt;=10^9</div>

</div>