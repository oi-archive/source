<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　设有一个N＊M（l≤ N≤50， l≤ M≤ 50）的街道。n和m表示横竖街道数。<br/>
　　规定行人从A(1,1)出发，在街道上只能向东或北方向行走。<br/>
　　N＝3，M=3的街道图，从A出发到达B共有6条可供行走的路。<br/>
　　若在N＊M的街道中，设置一个矩形障碍区域（包括围住该区域的街道和点）不让行人通行。<br/>
　　此矩形障碍区域用2对顶点坐标给出,前图中的2对顶点坐标为:(2，2),(8，4),此时从 A出发到达B的路径仅有两条。<br/>
<br/>
　　程序要求：<br/>
<br/>
　　任务一：给出N，M后，求出所有从A出发到达B的路径的条数。<br/>
<br/>
　　任务二：给出N，M，同时再给出此街道中的矩形障碍区域的2对顶点坐标(X1,y1), （X2，Y2），然后求出此种情况下所有从A出发到达B的路径的条数。<br/>
　　如果答案太大，输出最后20位。</div>
# 输入格式

<div class="pdcont">　　第一行两个数n和m。<br/>
　　第二行为X1,Y1,X2,Y2.如果是任务一，则第二行为4个0.</div>
# 输出格式

<div class="pdcont">　　输出走路方案数。</div>
# 样例输入

<div class="pddata">3 3<br/>
0 0 0 0</div>
# 样例输出

<div class="pddata">6</div>
# 样例输入

<div class="pddata">50 50<br/>
2 2 49 49</div>
# 样例输出

<div class="pddata">2</div>
# 数据规模和约定

<div class="pdcont">　　1&lt;=N,M&lt;=50</div>

</div>