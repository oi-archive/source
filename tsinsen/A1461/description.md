<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在PMP去世之前，他签署了一份关于快速公交系统（BRT）的协议，旨在用优化旅程期望时间的方式来提高公共交通质量。你应该替PMP完成他最后的协议。<br/>
　　每条BRT路线都是一条经过n个交叉路口的笔直公路。每个路口都有一个红绿灯，红灯和绿灯定时循环出现。在时刻0所有灯都是绿灯。在绿灯的g秒内，车辆允许通过。绿灯时间过后灯变为持续r秒的红色，此时车辆禁止通过。如果一辆车在绿灯变红灯的一瞬间到达路口，它应该停下，但是如果它在红灯变绿灯的一瞬间到达路口，它可以顺利通过。<br/>
<br/>
<img src="source/tsinsen/A1461/img/aHR0cDovL2NvZGVmb3JjZXMucnUvcmVuZGVyZXIvMzU1MWFiNWY2Y2YyYWI1YTA3OGMzMWU3MmY3YWQ4ZGFiMjcyYWVlZS5wbmc=.png"/><br/>
　　每个红绿灯有着同样的周期并且保持同步。换句话说，所有灯的红灯时间和绿灯时间是相等的且在时刻0所有灯都刚变为绿色。<br/>
　　BRT公司已经计算出一辆公交车通过每段路的时间。一段路指的是两个红绿灯或一个红绿灯与起点（或终点）站之间的距离。更准确的说，BRT专家提供了n+1个正整数<i>l</i><sub><i>i</i></sub>，表示一辆公交车经过从起点到终点的第i段路所需的时间（单位：秒）。<i>l</i><sub>1</sub>表示从起点到第一个路口的时间。<i>l</i><sub><i>n</i> + 1表示从最后一个路口到终点的时间。</sub><br/>
　　在一天里有q辆公交车从起点站出发。第i辆车的出发时刻为<i>t</i><sub><i>i</i></sub>（单位：秒）。BRT公司的决策者想要知道每辆车到达终点站的时刻。<br/>
　　公交车可被视为质点。只要可以，公交车就会向前开。公交车之间不会互相影响。</div>
# 输入格式

<div class="pdcont">　　第一行包含三个用空格隔开的正整数n，g，r(1 ≤ <i>n</i> ≤ 10<sup>5</sup>, 2 ≤ <i>g</i>,<i>r</i> ≤ 10<sup>9</sup>)，分别表示交叉路口的数目，绿灯的持续时间和红灯的持续时间。接下来一行包含n+1个正整数<i>l</i><sub><i>i</i></sub> (1 ≤ <i>l</i><sub><i>i</i></sub> ≤ 10<sup>9</sup>)，表示通过从起点到终点的每段路所需的时间。<br/>
　　下一行包含一个整数q(1 ≤ <i>q</i> ≤ 10<sup>5</sup>)，表示一天的公交车数目。接下来q行的第i行表示包含一个整数<i>t</i><sub><i>i</i></sub> (1 ≤ <i>t</i><sub><i>i</i></sub> ≤ 10<sup>9</sup>)，表示第i辆车从起点站离开的时刻。</div>
# 输出格式

<div class="pdcont">　　共q行，在第i行输出第i辆公交车到达终点站的时刻。</div>
# 样例输入

<div class="pddata">1 3 2<br/>
5 2<br/>
5<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5</div>
# 样例输出

<div class="pddata">8<br/>
9<br/>
12<br/>
12<br/>
12</div>
# 数据规模和约定

<div class="pdcont">　　对于25%的数据，2 ≤ <i>g</i>，<i>r，n</i> ≤ 20<br/>
　　对于100%的数据，1 ≤ <i>n</i> ≤ 10<sup>5</sup>, 2 ≤ <i>g</i>,<i>r</i> ≤ 10<sup>9</sup></div>

</div>