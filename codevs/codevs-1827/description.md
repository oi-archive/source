<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>相信大家都玩过贪食蛇游戏，现在有一个改版贪食蛇游戏，跟传统的贪食蛇游戏一样，贪食蛇在活动区域内运动，吃食物，但是这个改版的贪食蛇游戏有着一些特别的规则。</p>
<p> </p>
<p>活动区域：</p>
<p>贪食蛇的活动区域是一个R行C列的网格A，贪食蛇活动不能超过这个网格的范围。第i行第j列的方格用Ai,j表示。每个方格有一个整数权值，记作w(Aij)。0&lt;=w(Aij)&lt;=8，w(Aij)=0时，Aij禁止进入；w(Aij)&gt;0时，Aij允许进入。</p>
<p> </p>
<p>方向：</p>
<p>对于P=(X0,Y0)、Q=(X1,Y1)，有以下四种基本方向：</p>
<p>l 正左(L)：X0=X1且Y0=Y1-1，则称P位于Q的正左方向。</p>
<p>l 正右(R)：X0=X1且Y0=Y1+1，则称P位于Q的正右方向。</p>
<p>l 正上(U)：X0=X1-1且Y0=Y1，则称P位于Q的正上方向。</p>
<p>l 正下(D)：X0=X1+1且Y0=Y1，则称P位于Q的正下方向。</p>
<p> </p>
<p>贪食蛇：</p>
<p>贪食蛇B是占据若干方格的图形，占据的方格数为贪食蛇的长度，记为m，则贪食蛇从头到尾，用B1、B2、……、Bm表示。记p为贪食蛇的形态，若Bi位于第Xi行第Yi列，则p(Bi)=(Xi,Yi)。初始情况下，m=4，且运动过程中始终需要满足以下限制：</p>
<p>l 对于Bi和Bi+1(1&lt;=i&lt;m)，就是贪食蛇的前、后相邻两部分，必须满足Bi位于Bi+1的L、R、U、D四个方向之一。</p>
<p>l 对于Bi和Bj(1&lt;=i&lt;j&lt;=m)，p(Bi)=(Xi,Yi)，p(Bj)=(Xj,Yj)，需要满足Xi!=Xj或Yi!=Yj。也就是说，贪食蛇身体的任意一部分不能相交。</p>
<p> </p>
<p>食物：</p>
<p>贪食蛇的活动区域内存在一些食物。每个食物位于一个允许进入的方格上，食物不会重叠。每个食物只能被吃一次。</p>
<p> </p>
<p>贪食蛇的运动：</p>
<p>如果贪食蛇的头部B1的L、R、U、D四个方向之一的Aij能进入，且Aij上不存在食物，则贪食蛇可以向该方向运动，新的头部位于Aij上。记p’为贪食蛇新的形态，则：</p>
<p>l p’(Bk)=p(Bk-1)，当2&lt;=k&lt;=m。</p>
<p>l p’(Bk)=(i,j)，当k=1</p>
<p> </p>
<p>贪食蛇的进食：</p>
<p>如果贪食蛇的头部B1的L、R、U、D四个方向之一的Aij能进入，且Aij上存在食物，则贪食蛇可以向该方向进食，新的头部位于Aij上，蛇的新长度m’=m+1。记p’为贪食蛇新的位置，则：</p>
<p>l p’(Bk)=p(Bk-1)，当2&lt;=k&lt;=m’。</p>
<p>l p’(Bk)=(i,j)，当k=1</p>
<p> </p>
<p>注意：运动或进食后的贪食蛇形态，仅仅需要考虑变换后的形态是否满足限制，不需要考虑变换的过程。也就是说，原来形态合法的贪食蛇的头部可以运动到尾部的位置，因为在变换后头部和尾部仍不会重叠。</p>
<p> </p>
<p>运动或进食所需要的时间：</p>
<p>贪食蛇运动或进食，需要消耗时间。设运动或进食前头部所在的方格是P，运动或进食后头部所在的方格是Q，则此次运动或进食的所消耗的时间为|w(P)-w(Q)|+1。</p>
<p> </p>
<p>游戏的会在开始前给出贪食蛇的初始位置和所有食物的位置。你的任务是，以最少的时间令贪食蛇吃完所有食物。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，两个正整数R、C。</p>
<p>接下来R行，每行C个没有空格分隔的数字。其中第i行第j个数字为w(Aij)。</p>
<p>接下来4行，每行2个正整数。第i行的两个整数Xi、Yi，表示p(Bi)=(Xi,Yi)。</p>
<p>接下来一个正整数N，表示食物的数量。</p>
<p>接下来N行，每行2个正整数i、j，表示Aij上存在一个食物。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">如果贪食蛇不能吃到所有的食物，输出&ldquo;No&nbsp;solution.&rdquo;（不包括引号）。</p>
<p class="p0">否则，输出：</p>
<p class="p0">第一行，一个整数，表示所需花费的时间；</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p>
<p>11011</p>
<p>11011</p>
<p>11011</p>
<p>11011</p>
<p>11411</p>
<p>1 1</p>
<p>2 1</p>
<p>3 1</p>
<p>4 1</p>
<p>4</p>
<p>5 5</p>
<p>4 4</p>
<p>2 5</p>
<p>1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>21</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，N &lt;= 1。</p>
<p>对于40%的数据，N &lt;= 2。</p>
<p>对于60%的数据，N &lt;= 3。</p>
<p>对于100%的数据，N &lt;= 4。</p>
<p> </p>
<p>对于30%的数据，R * C &lt;= 36。</p>
<p>对于100%的数据，R &lt;= 12，C &lt;= 12。</p>
</div>
</div>