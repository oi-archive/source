<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定一长度为n的正整数序列a，有q次询问，每次询问一段区间内所有数的lcm(即最小公倍数)。由于答案可能很大，输出答案模1000000007。</div>
# 输入格式

<div class="pdcont">　　第一行，两个整数，n, q，分别表示数列长度和询问个数。<br/>
　　下面n行，每行一个整数，第i行的整数为a<sub>i</sub>。<br/>
　　下面q行，每行两个整数l, r，表示询问下标i在[l, r]范围内的a<sub>i</sub>的lcm。</div>
# 输出格式

<div class="pdcont">　　q行。对于每个询问，输出一行，表示对应的答案。</div>
# 样例输入

<div class="pddata">3 3<br/>
123<br/>
234<br/>
345<br/>
1 2<br/>
2 3<br/>
1 3</div>
# 样例输出

<div class="pddata">9594<br/>
26910<br/>
1103310</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">测试数据编号<br/>
</td><td valign="top" style="border:solid 1.0pt">规模和约定<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1, 2<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=1000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3, 4<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=5000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5, 6<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=20000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7, 8<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=30000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9, 10<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=40000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">11, 12<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=50000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">13, 14<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=80000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">15, 16<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=100000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">17, 18, 19, 20<br/>
</td><td valign="top" style="border:solid 1.0pt">n, q&lt;=100000 数列a中每个数能表示为不超过100的素数的积<br/>
</td></tr></tbody></table>　　对于所有测试点，数列a中每个数满足1&lt;=a<sub>i</sub>&lt;=1000000000。</div>

</div>