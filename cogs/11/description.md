# 题目描述


<h3>
<b>【问题描述】</b> 
</h3>
<div>
    一个工厂每天生产若干商品，需运输到销售部门进行销售。从产地到销地要经过某些城镇，有不同的路线可以行走，每条两城镇间的公路都有一定的流量限制。请你计算，在不考虑其它车辆使用公路的前提下，如何充分利用所有的公路，使产地运输到销地的商品最多，最多能运输多少商品。
</div>
<h3>
【输入格式】
</h3>
<div>
输入文件有若干行<br/>
第一行，一个整数n，表示共有n个城市$(2&lt;=n&lt;=100)$,产地是1号城市，销地是n号城市。<br/>
下面有n行,每行有n个数字。第p行第q列的数字表示城镇p与城镇q之间有无公路连接。数字为0表示无，大于0表示有公路，且该数字表示该公路流量。
</div>
<h3>
【输出格式】
</h3>
<div>
输出文件有一行<br/>
第一行，1个整数max，表示最大流量为max。
</div>
<h3>
【输入样例】maxflowa.in
</h3>
<p>
6<br/>
0 4 8 0 0 0<br/>
0 0 4 4 1 0<br/>
0 0 0 2 2 0<br/>
0 0 0 0 0 7<br/>
0 0 0 6 0 9
</p>
<h3>
<span style="font-family:sans-serif;font-size:20px;background-color:aliceblue;">【输出样例</span><span style="font-family:sans-serif;font-size:20px;background-color:aliceblue;">】maxflowa.out</span>
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">8</span>
</p>
