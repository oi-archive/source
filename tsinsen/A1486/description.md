<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出一棵N个点的树，每个点有各自的权值，小A想选出一条简单路径，使得这条路径上的点的权值的异或和最大。另外，小A有一些喜欢的点，他希望在这条路径上经过至少K个自己喜欢的点。</div>
# 输入格式

<div class="pdcont">　　第一行包括两个整数N, K，分别表示树的点数和路径上至少包含的小A喜欢的点的数量。<br/>
　　接下来一行N个整数，每个数均为0或1，小A喜欢第i个点当且仅当这一行的第i个数是1。<br/>
　　接下来一行N个整数V<sub>1</sub>, V<sub>2</sub>, …, V<sub>N</sub>，其中第i个数表示第i个点的权值。<br/>
　　最后N-1行，每行两个整数u, v，表示树的一条边。</div>
# 输出格式

<div class="pdcont">　　如果不存在这样的简单路径，输出-1。否则输出最大的异或和。</div>
# 样例输入

<div class="pddata">3 1<br/>
1 1 1<br/>
0 4 7<br/>
1 2<br/>
2 3</div>
# 样例输出

<div class="pddata">7</div>
# 样例输入

<div class="pddata">3 2<br/>
1 0 1<br/>
3 5 6<br/>
1 2<br/>
2 3</div>
# 样例输出

<div class="pddata">0</div>
# 样例输入

<div class="pddata">4 4<br/>
1 1 1 1<br/>
10 10 10 10<br/>
1 2<br/>
1 3<br/>
1 4</div>
# 样例输出

<div class="pddata">-1</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">测试点标号<br/>
</td><td valign="top" style="border:solid 1.0pt">N的范围<br/>
</td><td valign="top" style="border:solid 1.0pt">K的范围<br/>
</td><td valign="top" style="border:solid 1.0pt">V<sub>i</sub>的范围<br/>
</td><td valign="top" style="border:solid 1.0pt">其它特点<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">N=2<br/>
</td><td valign="top" style="border:solid 1.0pt">K=0<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤10<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤1000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">这棵树是一条链<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤1000<br/>
</td><td valign="top" style="border:solid 1.0pt">K=0<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">这棵树是一条链<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤4000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤30000<br/>
</td><td valign="top" style="border:solid 1.0pt">K=0<br/>
</td><td valign="top" style="border:solid 1.0pt">V<sub>i</sub>≤7<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤40000<br/>
</td><td valign="top" style="border:solid 1.0pt">K=0<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤40000<br/>
</td><td valign="top" style="border:solid 1.0pt">K=0<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤50000<br/>
</td><td valign="top" style="border:solid 1.0pt">K=0<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">这棵树是一条链<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤50000<br/>
</td><td valign="top" style="border:solid 1.0pt">K=0<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">11<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤60000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">V<sub>i</sub>≤7<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">12<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤60000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">这棵树是一条链<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">13<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤70000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">V<sub>i</sub>≤10<sup>7</sup><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">14<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤70000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">V<sub>i</sub>≤10<sup>7</sup><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">15<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤80000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">16<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤80000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">17<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤90000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">18<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤90000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">19<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">20<br/>
</td><td valign="top" style="border:solid 1.0pt">N≤100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr></tbody></table>　　对于100%的数据，1≤N≤100000, 0≤K≤N, 0≤V<sub>i</sub>≤10<sup>9</sup>, 保证输入的是一棵合法的树.</div>

</div>