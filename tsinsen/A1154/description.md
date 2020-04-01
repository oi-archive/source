<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　乐乐是一个聪明而又勤奋好学的孩子。他总喜欢探求事物的规律。一天，他突然对数的正整数次幂产生了兴趣。<br/>
　　众所周知，2的正整数次幂最后一位数总是不断的在重复2，4，8，6，2，4，8，6……我们说2的正整数次幂最后一位的循环长度是4（实际上4的倍数都可以说是循环长度，但我们只考虑最小的循环长度）。类似的，其余的数字的正整数次幂最后一位数也有类似的循环现象：<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">数字<br/>
</td><td valign="top" style="border:solid 1.0pt">循环<br/>
</td><td valign="top" style="border:solid 1.0pt">循环长度<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2、4、8、6<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">3、9、7、1<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">4、6<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">7、9、3、1<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">8、4、2、6<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">9、1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td></tr></tbody></table>　　这时乐乐的问题就出来了：是不是只有最后一位才有这样的循环呢？对于一个整数n的正整数次幂来说，它的<b>后k位</b>是否会发生循环？如果循环的话，循环长度是多少呢？<br/>
　　注意：<br/>
　　1． 如果n的某个正整数次幂的位数不足k，那么不足的高位看做是0。<br/>
　　2． 如果循环长度是L，那么说明对于任意的正整数a，n的a次幂和a + L次幂的最后k位都相同。</div>
# 输入格式

<div class="pdcont">　　只有一行，包含两个整数n（1 &lt;= n &lt; 10<sup>100</sup>）和k（1 &lt;= k &lt;=  100），n和k之间用一个空格隔开，表示要求n的正整数次幂的最后k位的循环长度。</div>
# 输出格式

<div class="pdcont">　　t包括一行，这一行只包含一个整数，表示循环长度。如果循环不存在，输出-1。</div>
# 样例输入

<div class="pddata">32 2</div>
# 样例输出

<div class="pddata">4</div>
# 数据规模和约定

<div class="pdcont">　　对于30%的数据，k &lt;= 4；<br/>
　　对于全部的数据，k &lt;= 100。</div>

</div>