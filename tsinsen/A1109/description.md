<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　将1，2，···,9共9个数排成下列形态的三角形。<br/>
<img src="source/tsinsen/A1109/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VEc5ZUc2ZTY=.do" width="83" height="59"/><br/>
　　其中：a～i分别表示1，2，······,9中的一个数字，并要求同时满足下列条件：<br/>
　　（1）a&lt;f&lt;i;<br/>
　　（2）b&lt;d, g&lt;h, c&lt;e<br/>
　　（3）a+b+d+f=f+g+h+i=i+e+c+a=P<br/>
　　程序要求：<br/>
　　根据输入的边长之和P<br/>
　　输出所有满足上述条件的三角形的个数以及其中的一种方案。<br/>
　　若有多种方案输出字典序最小的那种。若无解输出NO。</div>
# 输入格式

<div class="pdcont">　　输入一行一个数表示P。</div>
# 输出格式

<div class="pdcont">　　无解输出一行NO，否则第一行是方案数，接下来是字典序最小的方案。每行的数之间用一个空格隔开。具体见样例。</div>
# 样例输入

<div class="pddata">23</div>
# 样例输出

<div class="pddata">2<br/>
7<br/>
2 3<br/>
6 4<br/>
8 1 5 9</div>

</div>