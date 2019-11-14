<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　下面是一段实现冒泡排序算法的C++代码：<br/>
<br/>
　　for (int i=1;i&lt;n;i++)<br/>
　　for (int j=1;j&lt;=n-i;j++)<br/>
　　if (a[j]&gt;a[j+1])<br/>
　　swap(a[j],a[j+1]);<br/>
<br/>
<br/>
<br/>
　　其中待排序的a数组是一个1~n的排列，swap函数将交换数组中对应位置的值。<br/>
　　对于给定的数组a以及给定的非负整数k，使用这段代码执行了正好k次swap操作之后数组a中元素的值会是什么样的呢？</div>
# 输入格式

<div class="pdcont">　　输入文件共2行。<br/>
　　第1行包含空格隔开的一个正整数n和一个非负整数k；<br/>
　　第2行包含n个空格隔开的互不相同的正整数，表示初始时a数组中的排列。</div>
# 输出格式

<div class="pdcont">　　输出文件共1行。<br/>
　　若在执行完整个代码之后执行swap的次数仍不够k，那么输出一个字符串”Impossible!”(不含引号)，否则按顺序输出执行swap操作k次之后数组a的每一个元素，用空格隔开。</div>
# 样例输入

<div class="pddata">1 1<br/>
1</div>
# 样例输出

<div class="pddata">Impossible!</div>
# 样例输入

<div class="pddata">5 5<br/>
5 4 3 2 1</div>
# 样例输出

<div class="pddata">3 4 2 1 5</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">测试点<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=<br/>
</td><td valign="top" style="border:solid 1.0pt">k&lt;=<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">10^12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">5000<br/>
</td><td valign="top" style="border:solid 1.0pt">10^12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">20000<br/>
</td><td valign="top" style="border:solid 1.0pt">10^12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">10^6<br/>
</td><td valign="top" style="border:solid 1.0pt">10^6<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">10^6<br/>
</td><td valign="top" style="border:solid 1.0pt">2*10^6<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">10^6<br/>
</td><td valign="top" style="border:solid 1.0pt">2*10^6<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">10^5<br/>
</td><td valign="top" style="border:solid 1.0pt">10^12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">10^5<br/>
</td><td valign="top" style="border:solid 1.0pt">10^12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">10^6<br/>
</td><td valign="top" style="border:solid 1.0pt">10^12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">10^6<br/>
</td><td valign="top" style="border:solid 1.0pt">10^12<br/>
</td></tr></tbody></table></div>

</div>