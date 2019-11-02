<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>火星探险队的登陆舱将在火星表面着陆，登陆舱内有多部障碍物探测车。登陆舱着陆后，<br>探测车将离开登陆舱向先期到达的传送器方向移动。探测车在移动中还必须采集岩石标本。<br>每一块岩石标本由最先遇到它的探测车完成采集。每块岩石标本只能被采集一次。岩石标本<br>被采集后，其他探测车可以从原来岩石标本所在处通过。探测车不能通过有障碍的地面。本<br>题限定探测车只能从登陆处沿着向南或向东的方向朝传送器移动，而且多个探测车可以在同<br>一时间占据同一位置。如果某个探测车在到达传送器以前不能继续前进，则该车所采集的岩<br>石标本将全部损失。</p>
<p> </p>
<p>用一个PXQ 网格表示登陆舱与传送器之间的位置。登陆舱的位置在(X1,Y1)处，传送器<br>的位置在(XP ,YQ)处。<br>X1,Y1 X2, Y1 X3, Y1 ... XP-1, Y1 XP, Y1<br>X1,Y2 X2, Y2 X3, Y2 ... XP-1, Y2 XP, Y2<br>X1, Y3 X2, Y3 X3,Y3 ... XP-1, Y3 XP, Y3<br>... ...<br>X1,YQ-1 X2, YQ-1 X3, YQ-1 ... XP-1, YQ-1 XP, YQ-1<br>X1,YQ X2, YQ X3, YQ ... XP-1, YQ XP ,YQ<br>给定每个位置的状态，计算探测车的最优移动方案，使到达传送器的探测车的数量最多，<br>而且探测车采集到的岩石标本的数量最多。<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行为探测车数，第2 行为P的值，第3 行为<br>Q 的值。接下来的Q 行是表示登陆舱与传送器之间的位置状态的PXQ 网格。用3 个数字表<br>示火星表面位置的状态：0 表示平坦无障碍，1表示障碍，2 表示石块。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>程序运行结束时，将每个探测车向传送器移动的序列输出<span style="font-size: 10px;">。每行包</span><span style="font-size: 10px;">含探测车号和一个移动方向，0 表示向南移动，1 表示向东移动。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>10<br>8<br>0 0 0 0 0 0 0 0 0 0<br>0 0 0 0 0 1 1 0 0 0<br>0 0 0 1 0 2 0 0 0 0<br>1 1 0 1 2 0 0 0 0 1<br>0 1 0 0 2 0 1 1 0 0<br>0 1 0 1 0 0 1 1 0 0<br>0 1 2 0 0 0 0 1 0 0<br>0 0 0 0 0 0 0 0 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 1<br>1 1<br>1 1<br>1 1<br>1 0<br>1 0<br>1 1<br>1 0<br>1 0<br>1 0<br>2 1<br>2 1<br>2 1<br>2 1<br>2 0<br>2 0<br>2 0<br>2 0<br>2 1<br>2 0<br>2 0<br>2 1<br>2 0<br>2 1<br>2 1<br>2 1</p>

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