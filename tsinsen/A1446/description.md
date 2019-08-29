<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Fibonacci数列模10^13下是这样定义的：<br/>
　　1、F0 = 0, F1 = 1<br/>
　　2、Fi = (Fi-1 + Fi-2) mod (10^13) （当i &gt; 1）<br/>
　　John想知道x是否在这个数列当中出现过，如果出现过，最早出现在哪个位置。</div>
# 输入格式

<div class="pdcont">　　输入包括一行：一个整数x，表示John想询问的数字，0&lt;=x&lt;10^13</div>
# 输出格式

<div class="pdcont">　　输出包括一行：如果x在上述数列中出现过，则输出其最早出现的位置，如果没有出现过，则输出-1</div>
# 样例输入

<div class="pddata">13</div>
# 样例输出

<div class="pddata">7</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号</td><td style="border:solid 1.0pt">x</td><td style="border:solid 1.0pt">答案</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1</td><td style="border:solid 1.0pt">5</td><td style="border:solid 1.0pt">/</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2</td><td style="border:solid 1.0pt">34</td><td style="border:solid 1.0pt">/</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3~6</td><td style="border:solid 1.0pt">/</td><td style="border:solid 1.0pt">答案&lt;=10^6</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7~12</td><td style="border:solid 1.0pt">/</td><td style="border:solid 1.0pt">答案&lt;=10^9</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">13~20</td><td style="border:solid 1.0pt">/</td><td style="border:solid 1.0pt">答案在2^63内</td></tr></tbody></table></div>

</div>