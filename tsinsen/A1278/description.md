<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　铭铭有n个十分漂亮的珠子和若干根颜色不同的绳子。现在铭铭想用绳子把所有的珠子连接成一个整体。<br/>
　　现在已知所有珠子互不相同，用整数1到n编号。对于第i个珠子和第j个珠子，可以选择不用绳子连接，或者在ci,j根不同颜色的绳子中选择一根将它们连接。如果把珠子看作点，把绳子看作边，将所有珠子连成一个整体即为所有点构成一个连通图。特别地，珠子不能和自己连接。<br/>
　　铭铭希望知道总共有多少种不同的方案将所有珠子连成一个整体。由于答案可能很大，因此只需输出答案对1000000007取模的结果。</div>
# 输入格式

<div class="pdcont">　　标准输入。输入第一行包含一个正整数n，表示珠子的个数。接下来n行，每行包含n个非负整数，用空格隔开。这n行中，第i行第j个数为ci,j。</div>
# 输出格式

<div class="pdcont">　　标准输出。输出一行一个整数，为连接方案数对1000000007取模的结果。</div>
# 样例输入

<div class="pddata">3<br/>
0 2 3<br/>
2 0 4<br/>
3 4 0</div>
# 样例输出

<div class="pddata">50</div>
# 样例说明

<div class="pdcont">　　按每对珠子是否连接有以下四类连接方法。<br/>
<img width="403" height="140" src="source/tsinsen/A1278/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZFQ1bW5nUlE=.do"/><br/>
　　每类连接方法包含的方法数为包含的边对应的绳子的ci,j之积。<br/>
　　其中图(1)中有2×3×4=24种，图(2)有2×4=8种，图(3)有2×3=6种，图(4)有3×4=12种。共50种。</div>
# 数据规模及限制

<div class="pdcont">　　对于100%的数据，n为正整数，所有的ci,j为非负整数且不超过1000000007。保证ci,j=cj,i。每组数据的n值如下表所示。<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">编号<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">n<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">11<br/>
</td><td valign="top" style="border:solid 1.0pt">12<br/>
</td><td valign="top" style="border:solid 1.0pt">13<br/>
</td><td valign="top" style="border:solid 1.0pt">14<br/>
</td><td valign="top" style="border:solid 1.0pt">15<br/>
</td><td valign="top" style="border:solid 1.0pt">16<br/>
</td></tr></tbody></table></div>

</div>