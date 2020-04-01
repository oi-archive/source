<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Bessie不小心游荡出Farmer John的田地，而走进了相邻的农民的地。她举起一个木瓜，木<br>瓜对奶牛来说可是不可多得得美味。这个木瓜林像一般的威斯康星州的田地一样被分割成一个<br>R行C列的网格(1 &lt;= R &lt;= 40, 1 &lt;= C &lt;= 40)。Bessie可以从一个格沿著一条跟X轴或<br>Y轴平行的直线走到邻接的令一个格。Bessie发现一开始她自己在木瓜林的(1,1)，也就是第<br>一行第一列慢悠悠地咀嚼著木瓜。</p>
<p>Bessie总是用她最信赖地双筒望远镜去数每一个邻接的格的低掛著的木瓜的数目。然后她就游<br>荡到那个有最多没有被吃掉的木瓜的邻接的格子（保证这洋的格子只有一个）。</p>
<p>按照这种移动方法，最终Bessie总是会在(R,C)停止然后吃掉那裡的木瓜。</p>
<p>给定这个木瓜林的大小及每个格的木瓜数F_ij(1 &lt;= F_ij &lt;= 100), 要求Bessie一共吃了<br>多少个木瓜。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第一行: 两个空格隔开的整数R和C.</p>
<p>* 第2到R+1行: 第i+1行有C个空格隔开的整数，表示第i行的每个格的水果数。也就是F_i1, <br> F_i2, ..., F_iC.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>* 第一行: 一个单独的整数，表示到Bessie吃完右下角(R,C)的木瓜回到牛棚的时候為止，<br /> 一共在木瓜林吃掉了多少个木瓜。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 4<br>3 3 4 5<br>4 5 3 2<br>1 7 4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>39</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>Bessie按照下图数字旁边的字母的顺序吃掉木瓜。</p>
<p>(1,1) ---&gt; (1,C)<br> <br>(1,1) 3a 3 4g 5h (1,C)</p>
<p>| 4b 5c 3f 2i |<br> <br>(R,1) 1 7d 4e 2j (R,C)</p>
<p>(R,1) ---&gt; (R,C)<br>她吃了39个木瓜，剩下4个没有吃（也就是说除了2个格幸免於难，剩下的格子都被Bessie扫<br>荡过了）。</p>
<p> </p>
</div>
</div>