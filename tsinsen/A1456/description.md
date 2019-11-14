<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Vasya想购买一台新冰箱。一台冰箱是一个整数边长的长方体。在Vasya的估计中，为了满足自己的日常所需，这台冰箱的容积必须至少为V。Vasya是一个极简主义者，因此他希望所买冰箱容积恰为V。另外，为了清洁方便，他希望这台冰箱的表面积S最小。<br/>
　　众所周知，三边长为a,b,c的长方体的体积V=abc，表面积S=2*(ab+bc+ac)<br/>
　　给定容积V，帮助Vasya找到冰箱的一组边长a,b,c，使得其表面积最小。</div>
# 输入格式

<div class="pdcont">　　第一行包含一个整数t，表示测试数据的组数。<br/>
　　接下来有t组测试数据，每组数据通过给出素因子分解，描述了一个整数V。<br/>
　　若V=p1^a1*p2^a2*…*pk^ak，其中pi是互异的素数，ai&gt;0。<br/>
　　那么这组测试数据的第一行是一个整数k<br/>
　　接下来有k行，每行两个整数pi,ai，给出了V的一个素因子pi及pi的次数ai。</div>
# 输出格式

<div class="pdcont">　　共t行，第i行描述的是第i组数据的答案：4个整数，分别表示最小的表面积S以及该长方体的三边长a,b,c。<br/>
　　若有多组答案，输出任意一组。可以以任意的顺序输出三边长。</div>
# 样例输入

<div class="pddata">3<br/>
1<br/>
2 3<br/>
1<br/>
17 1<br/>
3<br/>
3 1<br/>
2 3<br/>
5 1</div>
# 样例输出

<div class="pddata">24 2 2 2<br/>
70 1 1 17<br/>
148 4 6 5</div>
# 数据规模和约定

<div class="pdcont">　　t&lt;=500<br/>
　　对于25%的数据，V&lt;=10^6<br/>
　　对于50%的数据，V&lt;=10^9<br/>
　　对于100%的数据，V&lt;=10^18<br/>
<br/>
　　ps:CF上时限太松了..改成1s</div>

</div>