<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　对于一个由平面上点组成的集合S，以及一个平面上的点p，函数f(p,S)当且仅当p在S的凸包内部（包括S的凸包的边界）时值为1，其余情况下其值为0。<br/>
　　现给定两个平面上的点集P={p_1,p_2,…,p_N }和A={a_1,a_2,…,a_M }，我们称A中的一个点a_i为极点，当且仅当其满足<br/>
<img src="source/tsinsen/A1347/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZU5iNWRyRjk=.do" width="183" height="58"/><br/>
　　也就是说，a_i不在任意 A 集合中非 a_i  的点与P组成的凸包内部。<br/>
　　请统计出集合A中极点的个数。</div>
# 输入格式

<div class="pdcont">　　输入第一行包含两个用空格隔开的正整数N和M；<br/>
　　第二行包含N个用空格隔开的整数对，第i个数对(x_i^p,y_i^p)表示点p_i的坐标；<br/>
　　第二行包含M个用空格隔开的整数对，第j个数对(x_j^a,y_j^a)表示点a_j的坐标。<br/>
　　对于同一个集合，输入数据保证不会出现坐标相同的两个点。</div>
# 输出格式

<div class="pdcont">　　输出包含一行一个整数，表示集合A中极点的个数。</div>
# 样例输入

<div class="pddata">4 5<br/>
6 3 7 -1 -6 -5 1 5<br/>
-5 -5 7 -5 9 -9 -10 11 -5 -6</div>
# 样例输出

<div class="pddata">3</div>
# 样例说明

<div class="pdcont">　　极点分别为(-10,11)，(9,-9)以及(-5,-6)。</div>
# 数据规模和约定

<div class="pdcont">　　对于10%的数据满足M=1；<br/>
　　对于30%的数据满足N,M≤50；<br/>
　　对于另外30%的数据满足N≤10，M≤20000；<br/>
　　对于100%的数据满足3≤N≤ 〖10〗^5,1≤M≤〖10〗^5，|x_i |,|y_i |≤〖10〗^6，且点集P的凸包面积不为0。</div>

</div>