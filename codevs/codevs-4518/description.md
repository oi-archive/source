<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun;">    一天,GD 和 MW 正在玩一款名叫大海战的游戏。</span><span style="font-family: SimSun;">游戏在一个 1*n 的棋盘上进行。一开始 GD 拥有 c 种战舰,每种战舰的宽度为
1,长度为 ci,共有 ti 个。GD 要将所有这些战舰放置在棋盘上,并且任意两艘
战舰间不能重叠(但可以相邻)。接下来,MW 进行 q 次“攻击”,每次攻击一个
1*1 的格子,而 MW 将告知他这次攻击是否“打中”了一艘战舰(或者它的某个
部分)。令人疑惑的是,每次 MW 都告诉 GD 说他没有打中任何一艘战舰,而这显
然是不现实的。现在 MW 把整个游戏的过程告诉了你,他想知道,最早在他的第
几次询问之后,可以断定 GD 一定(至少有一次)说了谎。 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">    第一行一个整数 t,表示测试数据的组数。对于每组数据,第一行三个整数 n,
c,q,代表棋盘的长度、战舰的种数和攻击的次数。接下来 c 行,每行两个整数
ci、ti,表示第 i 种战舰的长度和数量。(不同的战舰,长度可能相同。)接下来
一行 q 个整数,表示 MW 的攻击序列。 </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun; font-size: 12pt;">&nbsp; &nbsp; 对于每组数据,输出一个整数 ans,表示最早在第 ans 次操作后可以断定 GD
说了谎。特别地,如果一开始就不可能按要求摆上所有的战舰,输出 0;如果 q
次询问后都不能判断 GD 是否说了谎,则输出-1。&nbsp;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br></p><p>12 2 2</p><p>1 1</p><p>2 5</p><p>6 8</p><p>5 1 2</p><p>3 1</p><p>1 5</p><p>11 3 0</p><p>2 2</p><p>3 1</p><p>5 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br></p><p>-1</p><p>0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">样例解释</span><br></p><p><span style="font-family: SimSun;">    对于第一个样例,存在布阵{1,22,22,0,22,22,22}(0 表示没有放置),
使得第一次不会受到攻击;不存在一个布阵使得两次都没有受到攻击。</span><br></p><p><span style="font-family: SimSun;">    对于第二个样例,存在布阵{0,333,0},使得两次均不会受到攻击。
对于第三个样例,一开始就不可能把所有战舰合法地布置在棋盘上。 </span><br></p><p><br></p><p><span style="font-family: 'SimHei';">数据范围</span></p><p><span style="">  </span><span style="">对于100%的数据，1&lt;=t&lt;=5,n&gt;=1,c&gt;=1,q&gt;=0,1&lt;=qi&lt;=n,0&lt;=ci&lt;=100000，0&lt;=ti&lt;=100000。<br style="">   对于测试点1，n&lt;=1000000000，c&lt;=100000，q=0；<br style="">   对于测试点2、3，所有的ti均为1；<br style="">   对于测试点2-8，n&lt;=400000，c&lt;=100，q=1；<br style="">   对于测试点9，n&lt;=100，c=1，q&lt;=100；<br style="">   对于测试点10-14，n&lt;=200000，c=1，q&lt;=200000；<br style="">   对于测试点15、16，n&lt;=200，c=2，q&lt;=200；<br style="">   对于测试点17-20，n&lt;=4000，c=2，q&lt;=4000。</span></p>
</div>
</div>