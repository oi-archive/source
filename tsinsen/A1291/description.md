<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Please compress a string which consists of capital letters only. To compress the string, <i>N</i> rules are given, each of which is a string of three letters <i>c</i><sub>1</sub> <i>c</i><sub>2</sub> <i>c</i><sub>3</sub>, meaning that two consecutive letters <i>c</i><sub>2</sub> <i>c</i><sub>3</sub> can be replaced with one letter <i>c</i><sub>1</sub>.<br/>
　　Besides, there is a set <i>S</i> of letters. The final compressed string should only contain letters in <i>S</i>, as short as possible.</div>
# 输入格式

<div class="pdcont">　　The first line of the input is an integer <i>N</i>, the number of rules.<br/>
　　Each of the following <i>N</i> lines contains three capital letters, <i>c</i><sub>1</sub> <i>c</i><sub>2</sub> <i>c</i><sub>3</sub>.<br/>
　　The next line contains the string needed to be compressed and the last line contains <i>S</i>, the set of letters that can appear in the final string.</div>
# 输出格式

<div class="pdcont">　　The output should contain exactly one line with one integer, the shortest length of the final compressed string. If there is no solution, output –1.</div>
# 样例输入

<div class="pddata">4<br/>
ABC<br/>
BCC<br/>
CDD<br/>
AAA<br/>
CCDD<br/>
AD</div>
# 样例输出

<div class="pddata">1</div>
# Constraints

<div class="pdcont">　　For all test cases, <i>N</i> ≤ 5000, and the length of the original string is no larger than 100.</div>

</div>