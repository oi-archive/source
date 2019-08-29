<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给你n根火柴棍，你可以拼出多少个形如“A+B=C”的等式？等式中的A、B、C是用火柴棍拼出的整数（若该数非零，则最高位不能是0）。用火柴棍拼数字0-9的拼法如图所示：<br/>
<img width="863" height="188" src="source/tsinsen/A1167/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9M05xOEc1Rmc=.do"/><br/>
　　注意：<br/>
　　1. 加号与等号各自需要两根火柴棍<br/>
　　2. 如果A≠B，则A+B=C与B+A=C视为不同的等式（A、B、C&gt;=0）<br/>
　　3. n根火柴棍必须全部用上</div>
# 输入格式

<div class="pdcont">　　输入共一行，又一个整数n（n&lt;=24）。</div>
# 输出格式

<div class="pdcont">　　输出共一行，表示能拼成的不同等式的数目。</div>
# 输入输出样例1

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt"><b>输入</b><br/>
</td><td valign="top" style="border:solid 1.0pt"><b>输出</b><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">14<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td></tr></tbody></table></div>
# 输入输出样例1解释

<div class="pdcont">　　2个等式为0+1=1和1+0=1。</div>
# 输入输出样例2

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt"><b>输入</b><br/>
</td><td valign="top" style="border:solid 1.0pt"><b>输出</b><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">18<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td></tr></tbody></table></div>
# 输入输出样例2解释

<div class="pdcont">　　9个等式为：<br/>
　　0+4=4<br/>
　　0+11=11<br/>
　　1+10=11<br/>
　　2+2=4<br/>
　　2+7=9<br/>
　　4+0=4<br/>
　　7+2=9<br/>
　　10+1=11<br/>
　　11+0=11</div>

</div>