<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Answer在看过碟中谍后，对“X中X”很感兴趣，于是想探究“图中图”。<br/>
　　“图中图”的外图是一张由<b>M</b>个大节点组成的有<b>K</b>条边<b>(</b><b>无重边和自环)</b>的<b>无向无权图</b><b>(</b><b>不一定连通)</b>，外图中的每个大节点的内部又是一张由若干条边组成的<b>无向有权图</b>。<br/>
　　Answer想要构一张“图中图”，对大节点之间的边可以随便连<b>K</b>条，对每个大节点内部的无向图，Answer有一种生成方法：<br/>
　　1.      先确定一个长度为<b>N</b>的序列A<br/>
　　2.      对于每个大节点，确定一个在A中的区间[l<sub>i </sub>, r<sub>i</sub>]<br/>
　　3.      那么在第i个大节点中，<br/>
<b>边数=sigma(sum<sub>x</sub>+num<sub>x</sub><sup>3</sup>)  </b><b>区间[l<sub>i </sub>, r<sub>i</sub>]</b><b>中存在x</b><br/>
　　其中sum<sub>x</sub>为在区间[l<sub>i </sub>, r<sub>i</sub>]中比x小的数字个数，num<sub>x</sub>为区间[l<sub>i </sub>, r<sub>i</sub>]中等于x的数字个数。<br/>
　　设t为在区间[l<sub>i </sub>, r<sub>i </sub>]中出现的不重复的数字个数，那么每条边上的权值可以取1~t的任意正整数。<br/>
　　现在，Answer想要求出在给<b>M,K</b>,序列<b>A</b>和每个大节点的区间[l<sub>i </sub>, r<sub>i </sub>]的情况下，有多少张不同的“图中图”，由于方案数可能很大，你只需要输出方案数模P后的答案。<br/>
　　*对于大节点，Answer只关心边的情况，而不关心点的情况，每个大节点中的边是有标号的，两个方案不同当且仅当，M个大节点的连接状况不同或者至少其中有一个大节点的其中一条边的权值不同。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含四个正整数N,M,P,K。<br/>
　　第二行包含N个正整数A<sub>i</sub>。<br/>
　　以下M行，每行包含两个正整数l<sub>i</sub>,r<sub>i</sub>。<br/>
　　意义如上。</div>
# 输出格式

<div class="pdcont">　　输出一个整数，表示方案数模P后的值。</div>
# 样例输入

<div class="pddata">5 3 22 2<br/>
1 2 1 3 1<br/>
1 3<br/>
2 4<br/>
3 5</div>
# 样例输出

<div class="pddata">14</div>
# 样例说明

<div class="pdcont">　　外图中有3个大节点，那么连2条边，有3种连法<br/>
　　第一个大节点中有11条边，每条边可以取值1~2<br/>
　　第二个大节点中有6条边，每条边可以取值1~3<br/>
　　第三个大节点中有11条边，每条边可以取值1~2<br/>
　　所以总方案数模22得14</div>
# 数据规模和约定

<div class="pdcont">　　设P=p<sub>1</sub> <sup>c1</sup> *p<sub>2</sub><sup>c2</sup> *…*p<sub>t</sub><sup>ct</sup> ，p<sup>i</sup>为质数。<br/>
　　对于30%的数据，满足N,M≤1000,M<sup>2</sup>&lt;P&lt;10<sup>9</sup>且P是质数<br/>
　　另有20%的数据，满足N,M≤1000<br/>
　　对于100%的数据,满足N,M≤50000 , K≤M*(M-1)/2 , 0≤a<sub>i</sub>≤10<sup>9</sup><br/>
<sup>                  </sup>             p<sub>i</sub><sup>ci</sup> ≤100000 , P≤10<sup>9</sup></div>

</div>