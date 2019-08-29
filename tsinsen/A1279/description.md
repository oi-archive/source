<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　对于一个平面上点的集合P={(x<sub>i</sub>,y<sub>i</sub> )}，定义集合P的面积F(P)为点集P的凸包的面积。<br/>
　　对于两个点集A和B，定义集合的和为：<br/>
　　A+B={(x<sub>i</sub><sup>A</sup>+x<sub>j</sub><sup>B</sup>,y<sub>i</sub><sup>A</sup>+y<sub>j</sub><sup>B</sup> ):(x<sub>i</sub><sup>A</sup>,y<sub>i</sub><sup>A</sup> )∈A,(x<sub>j</sub><sup>B</sup>,y<sub>j</sub><sup>B</sup> )∈B}<br/>
　　现在给定一个N个点的集合A和一个M个点的集合B，求2F(A+B)。</div>
# 输入格式

<div class="pdcont">　　第一行包含用空格隔开的两个整数，分别为N和M；<br/>
　　第二行包含N个不同的数对，表示A集合中的N个点的坐标；<br/>
　　第三行包含M个不同的数对，表示B集合中的M个点的坐标。</div>
# 输出格式

<div class="pdcont">　　一共输出一行一个整数，2F(A+B)。</div>
# 样例输入

<div class="pddata">4 5<br/>
0 0 2 1 0 1 2 0<br/>
0 0 1 0 0 2 1 2 0 1</div>
# 样例输出

<div class="pddata">18</div>
# 数据规模和约定

<div class="pdcont">　　对于30%的数据满足N ≤ 200，M ≤ 200；<br/>
　　对于100%的数据满足N ≤ 10<sup>5</sup>，M ≤ 10<sup>5</sup>，|xi|, |yi| ≤ 10<sup>8</sup>。</div>

</div>