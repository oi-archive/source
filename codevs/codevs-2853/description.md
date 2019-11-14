<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>菜菜看到了一个游戏，叫做方格游戏~</p>
<p>游戏规则是这样的：</p>
<p>在一个n*n的格子中，在每个1*1的格子里都能获得一定数量的积分奖励，记左上角为(1,1)，右下角为(n,n)。游戏者需要选择一条(1,1)到(n,n)的路径，并获得路径上奖励的积分。对于路径当然也有要求啦，要求是只能往坐标变大的方向走【从(x,y)到(x+1,y)或者(x,y+1)】，走过2n-1个区域到达(n,n)。当然，获得的积分最高的就能取胜啦。</p>
<p>这时，菜菜看到了他的好友月月，于是邀请她来玩双人版的。双人版的规则就是在单人版的基础上加上一条两人的路线不能相同。月月知道菜菜的很聪明，怕输得太惨，就不太愿意和他玩。菜菜可慌了，于是定义了一个公平值D，这个公平值等于俩人所选择的路径所能获得的积分一一对应相减的差的绝对值之和，即D=sigma (|kxi-kyi|)|(kx，ky分别为菜菜，月月走过的每一个区域的丛林系数）。不过这可是个庞大的计算任务，菜菜找到了你，请你帮忙计算公平值的最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行，一个正整数n</p>
<p>    接下来的n行，每行n个整数，表示丛林中每个区域的公平值</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数Dmax，即公平值的最大值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1 2 3 4</p>
<p>1 5 3 2</p>
<p>8 1 3 4</p>
<p>3 2 1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，保证0＜n≤20</p>
<p>对于50%的数据，保证0＜n≤50</p>
<p>对于100%的数据，保证0＜n≤100且对于所有的i，j保证|Kij|≤300</p>
</div>
</div>