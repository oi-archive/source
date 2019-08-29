<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　输入一个正整数<i>n</i>，输出<i>n</i>!的值。<br/>
　　其中<i>n</i>!=1*2*3*…*<i>n</i>。</div>
# 算法描述

<div class="pdcont">　　<i>n</i>!可能很大，而计算机能表示的整数范围有限，需要使用高精度计算的方法。使用一个数组<i>A</i>来表示一个大整数<i>a</i>，<i>A</i>[0]表示<i>a</i>的个位，<i>A</i>[1]表示<i>a</i>的十位，依次类推。<br/>
　　将<i>a</i>乘以一个整数<i>k</i>变为将数组<i>A</i>的每一个元素都乘以<i>k</i>，请注意处理相应的进位。<br/>
　　首先将<i>a</i>设为1，然后乘2，乘3，当乘到<i>n</i>时，即得到了<i>n</i>!的值。</div>
# 输入格式

<div class="pdcont">　　输入包含一个正整数<i>n</i>，<i>n</i>&lt;=1000。</div>
# 输出格式

<div class="pdcont">　　输出<i>n</i>!的准确值。</div>
# 样例输入

<div class="pddata">10</div>
# 样例输出

<div class="pddata">3628800</div>

</div>