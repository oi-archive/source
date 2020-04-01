<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　设函数g(N)表示N的约数个数。<br/>
　　现在给出一个数M，求出所有M的约数x的g(x)的K次方和。<br/>
　　即计算<br/>
<img width="201" height="71" src="source/tsinsen/A1240/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RWhlSFJNQkE=.do"/></div>
# 输入格式

<div class="pdcont">　　第一行输入N，K。N表示M由前N小的素数组成。<br/>
　　接下来N行，<br/>
　　第i+1行有一个正整数Pi，表示第i小的素数A<sub>i</sub>有P<sub>i</sub>次。<br/>
　　等式：<br/>
<img width="222" height="32" src="source/tsinsen/A1240/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZmZkbUdMSHI=.do"/></div>
# 输出格式

<div class="pdcont">　　输出一个数，表示答案。只需输出最后答案除以1000000007的余数。</div>
# 样例输入

<div class="pddata">2 3<br/>
1<br/>
3</div>
# 样例输出

<div class="pddata">900</div>
# 样例说明

<div class="pdcont">　　M=2^1*3^3=54<br/>
　　M的约数有1,2,3,6,9,18,27,54.约数个数分别为1,2,2,4,3,6,4,8.<br/>
　　Answer=1^3+2^3+2^3+4^3+3^3+6^3+4^3+8^3=900</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">编号<br/>
</td><td valign="top" style="border:solid 1.0pt">N<br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">Pi&lt;=<br/>
</td><td valign="top" style="border:solid 1.0pt">编号<br/>
</td><td valign="top" style="border:solid 1.0pt">N<br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">Pi&lt;=<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">11<br/>
</td><td valign="top" style="border:solid 1.0pt">64970<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">2^63-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">12<br/>
</td><td valign="top" style="border:solid 1.0pt">71321<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">2^63-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">20101125<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">13<br/>
</td><td valign="top" style="border:solid 1.0pt">350<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">999<br/>
</td><td valign="top" style="border:solid 1.0pt">17651851<br/>
</td><td valign="top" style="border:solid 1.0pt">100000<br/>
</td><td valign="top" style="border:solid 1.0pt">14<br/>
</td><td valign="top" style="border:solid 1.0pt">250<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">5000<br/>
</td><td valign="top" style="border:solid 1.0pt">836954247<br/>
</td><td valign="top" style="border:solid 1.0pt">100000<br/>
</td><td valign="top" style="border:solid 1.0pt">15<br/>
</td><td valign="top" style="border:solid 1.0pt">110<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">4687<br/>
</td><td valign="top" style="border:solid 1.0pt">1073741823<br/>
</td><td valign="top" style="border:solid 1.0pt">100000<br/>
</td><td valign="top" style="border:solid 1.0pt">16<br/>
</td><td valign="top" style="border:solid 1.0pt">99<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">4321<br/>
</td><td valign="top" style="border:solid 1.0pt">123456789<br/>
</td><td valign="top" style="border:solid 1.0pt">100000<br/>
</td><td valign="top" style="border:solid 1.0pt">17<br/>
</td><td valign="top" style="border:solid 1.0pt">80<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">5216<br/>
</td><td valign="top" style="border:solid 1.0pt">368756432<br/>
</td><td valign="top" style="border:solid 1.0pt">100000<br/>
</td><td valign="top" style="border:solid 1.0pt">18<br/>
</td><td valign="top" style="border:solid 1.0pt">70<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">8080<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td><td valign="top" style="border:solid 1.0pt">100000<br/>
</td><td valign="top" style="border:solid 1.0pt">19<br/>
</td><td valign="top" style="border:solid 1.0pt">60<br/>
</td><td valign="top" style="border:solid 1.0pt">11<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">10086<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">2^63-1<br/>
</td><td valign="top" style="border:solid 1.0pt">20<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">12<br/>
</td><td valign="top" style="border:solid 1.0pt">2^31-1<br/>
</td></tr></tbody></table></div>

</div>