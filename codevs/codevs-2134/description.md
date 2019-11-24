<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>iPig在大肥猪学校刚上完了无聊的猪文课，天资聪慧的iPig被这门对他来说无比简单的课弄得非常寂寞，为了消除寂寞感，他决定和他的好朋友giPi（鸡皮）玩一个更加寂寞的游戏——捉迷藏。</p>
<p>但是，他们觉得，玩普通的捉迷藏没什么意思，还是不够寂寞，于是，他们决定玩寂寞无比的螃蟹版捉迷藏，顾名思义，就是说他们在玩游戏的时候只能沿水平或垂直方向走。一番寂寞的剪刀石头布后，他们决定iPig去捉giPi。由于他们都很熟悉大肥猪学校的地形了，所以giPi只会躲在大肥猪学校内<em>N</em>个隐秘地点，显然iPig也只会在那<em>N</em>个地点内找giPi。游戏一开始，他们从这<em>N</em>个隐秘地点之中选定一个地点，iPig保持不动，然后giPi用30秒的时间逃离现场（显然，giPi不会呆在原地）。然后iPig会随机地去找giPi，直到找到为止。由于iPig很懒，所以他到总是走最短的路径，而且，他选择起始点不是随便选的，他想找一个地点，使得该地点到（除了这个地点以外的）最远的地点和最近的地点的距离差最小。iPig现在想知道这个距离差最小是多少。</p>
<p>由于iPig现在手上没有电脑，所以不能编程解决这个如此简单的问题，所以他马上打了个电话，要求你帮他解决这个问题。iPig告诉了你大肥猪学校的<em>N</em>个隐秘地点的坐标，请你编程求出iPig的问题。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个整数<em>N</em>；<strong></strong></p>
<p>第2 ~ (<em>N</em> + 1)行：每行两个整数<em>X<sub>i</sub></em>，<em>Y<sub>i</sub></em>，表示第<em>i</em>个地点的坐标。<strong></strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，为距离差的最小值。</p>

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
<p>0 0</p>
<p>1 0</p>
<p>0 1</p>
<p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据中，2 &lt;= <em>N</em> &lt;= 1000；</p>
<p>100%的数据中，2 &lt;= <em>N</em> &lt;= 100000，0 &lt;= <em>X<sub>i</sub></em>, <em>Y<sub>i</sub></em> &lt;= 100000000。</p>
<p>数据保证没有重点。</p>
</div>
</div>