<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　著名科学家卢斯为了检查学生对进位制的理解，他给出了如下的一张加法表，表中的字母代表数字。 例如：<br/>
<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">+<br/>
</td><td valign="top" style="border:solid 1.0pt">L<br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">V<br/>
</td><td valign="top" style="border:solid 1.0pt">E<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">L<br/>
</td><td valign="top" style="border:solid 1.0pt">L<br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">V<br/>
</td><td valign="top" style="border:solid 1.0pt">E<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">V<br/>
</td><td valign="top" style="border:solid 1.0pt">E<br/>
</td><td valign="top" style="border:solid 1.0pt">KL<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">V<br/>
</td><td valign="top" style="border:solid 1.0pt">V<br/>
</td><td valign="top" style="border:solid 1.0pt">E<br/>
</td><td valign="top" style="border:solid 1.0pt">KL<br/>
</td><td valign="top" style="border:solid 1.0pt">KK<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">E<br/>
</td><td valign="top" style="border:solid 1.0pt">E<br/>
</td><td valign="top" style="border:solid 1.0pt">KL<br/>
</td><td valign="top" style="border:solid 1.0pt">KK<br/>
</td><td valign="top" style="border:solid 1.0pt">KV<br/>
</td></tr></tbody></table><br/>
<br/>
</td></tr></tbody></table></td></tr></tbody></table>　　其含义为：<br/>
　　L+L=L，L+K=K，L+V=V，L+E=E<br/>
　　K+L=K，K+K=V，K+V=E，K+E=KL                                                                            ……<br/>
　　E+E=KV<br/>
<br/>
<br/>
<br/>
　　根据这些规则可推导出：L=0，K=1，V=2，E=3<br/>
　　同时可以确定该表表示的是4进制加法</div>
# 输入格式

<div class="pdcont">　　输入包含n+1行，第一行为n（n≤9）表示以下表格的行数。<br/>
　　以下n行，每行包括n个字符串，每个字串间用空格隔开。（字串仅有一个为‘+’号，其它都由大写字母组成）</div>
# 输出格式

<div class="pdcont">　　程序输出：<br/>
　　第一行为各个字母表示什么数，格式如：L=0 K=1 ……<br/>
　　按大写字母字典序升序输出，格式为：大写字母+‘=’+数字+一个空格……。<br/>
　　第二行为加法运算是几进制的，即一个整数k<br/>
　　若不可能组成加法表，则应输出“ERROR！”</div>

</div>