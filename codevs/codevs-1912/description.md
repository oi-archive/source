<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个N*N 的方形网格，设其左上角为起点◎，坐标为（1，1），X 轴向右为正，Y<br>轴向下为正，每个方格边长为1，如图所示。一辆汽车从起点◎出发驶向右下角终点▲，其<br>坐标为（N，N）。在若干个网格交叉点处，设置了油库，可供汽车在行驶途中加油。汽车在<br>行驶过程中应遵守如下规则：</p>
<p>(1)汽车只能沿网格边行驶，装满油后能行驶K 条网格边。出发时汽车已装满油，在起<br>点与终点处不设油库。<br>(2)汽车经过一条网格边时，若其X 坐标或Y 坐标减小，则应付费用B，否则免付费用。<br>(3)汽车在行驶过程中遇油库则应加满油并付加油费用A。<br>(4)在需要时可在网格点处增设油库，并付增设油库费用C（不含加油费用A）。<br>(5)(1)～(4)中的各数N、K、A、B、C均为正整数，且满足约束：2 £ N £ 100，2 £ K £ 10。<br>设计一个算法，求出汽车从起点出发到达终点的一条所付费用最少的行驶路线。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是N，K，A，B，C的值。第二行起是一<br>个N*N 的0-1 方阵，每行N 个值，至N+1 行结束。方阵的第i 行第j 列处的值为1 表示在<br>网格交叉点（i，j）处设置了一个油库，为0 时表示未设油库。各行相邻两个数以空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>程序运行结束时，将最小费用输出</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 3 2 3 6<br>0 0 0 0 1 0 0 0 0<br>0 0 0 1 0 1 1 0 0<br>1 0 1 0 0 0 0 1 0<br>0 0 0 0 0 1 0 0 1<br>1 0 0 1 0 0 1 0 0<br>0 1 0 0 0 0 0 1 0<br>0 0 0 0 1 0 0 0 1<br>1 0 0 1 0 0 0 1 0<br>0 1 0 0 0 0 0 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>