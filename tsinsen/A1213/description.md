<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Lambda受任于某情报站，他的工作是获取敌人情报。一次他在破解密码系统时，得到了一个N位B进制数φ，满足φ≡V (mod M)。他发现组成φ的数字很奇特。为了验证φ的特殊性，他将所有模M为V的N位B进制数，按照各数位构成的集合分类，并想知道每一类数各有多少个。</div>
# 输入格式

<div class="pdcont">　　输入共一行，包含四个整数N, B, M, V。</div>
# 输出格式

<div class="pdcont">　　输出共2<i><sup>B</sup></i>-1行，每行包含一个集合S和整数Ans[S]，以单个空格隔开。集合S用其所有元素的递减序列表示，如{2, 0, 1}表示为“210”。Ans[S]表示数位集合为S的满足以上性质的数的数目。<br/>
　　集合按照字典序输出，每个集合只输出一次。由于Ans[S]可能很大，只需输出它除以10007的余数即可。</div>
# 样例输入

<div class="pddata">3 3 4 1</div>
# 样例输出

<div class="pddata">0 0<br/>
1 1<br/>
10 1<br/>
2 0<br/>
20 0<br/>
21 2<br/>
210 1</div>
# 样例说明

<div class="pdcont">　　在所有三位三进制数（100<sub>3</sub>~222<sub>3</sub>）中，模4为1的数为100<sub>3</sub>, 111<sub>3</sub>, 122<sub>3</sub>, 210<sub>3</sub>, 221<sub>3</sub>。数位集合为{1}的有1个（111<sub>3</sub>），数位集合为{1, 0}的有1个（100<sub>3</sub>），数位集合为{2, 1}的有2个（122<sub>3</sub>, 221<sub>3</sub>），数位集合为{2, 1, 0}的有1个（210<sub>3</sub>）。</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试数据<br/>
</td><td style="border:solid 1.0pt"><i>N</i><i></i><br/>
</td><td style="border:solid 1.0pt"><i>B</i><i></i><br/>
</td><td style="border:solid 1.0pt"><i>M</i><i></i><br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1~2<br/>
</td><td style="border:solid 1.0pt">≤10<br/>
</td><td rowspan="4" style="border:solid 1.0pt">≤3<br/>
</td><td rowspan="3" style="border:solid 1.0pt">≤12<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3~6<br/>
</td><td style="border:solid 1.0pt">≤10<sup>3</sup><br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7~10<br/>
</td><td rowspan="4" style="border:solid 1.0pt">≤10<sup>9</sup><br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">11~14<br/>
</td><td style="border:solid 1.0pt">≤120<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">15~18<br/>
</td><td rowspan="2" style="border:solid 1.0pt">≤10<br/>
</td><td style="border:solid 1.0pt">≤8<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">19~20<br/>
</td><td style="border:solid 1.0pt">≤40<br/>
</td></tr></tbody></table><br/>
　　对于15%的测试数据，gcd(B, M)&gt;1。<br/>
　　对于所有测试数据，2≤N, 2≤B, 0≤V</div>

</div>