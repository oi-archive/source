<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　Alice<span style="">和</span>Bob<span style="">玩了一个古老的游戏：首先画一个</span>n * n<span style="">的点阵（下图</span>n = 3<span style="">）</span> <span style="">　　接着，他们两个轮流在相邻的点之间画上红边和蓝边：</span></p><p><span style="">     <img src="/source/codevs/codevs-5972/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9ibG9iXzIwMTcwNDEyMjAwNjIzXzYwNy5wbmc=.png" title=""></span></p><p>    <span style="">直到围成一个封闭的圈（面积不必为</span>1<span style="">）为止，“封圈”的那个人就是赢家。因为棋盘实在是太大了</span>(n &lt;= 200)<span style="">，他们的游戏实在是太长了！他们甚至在游戏中都不知道谁赢得了游戏。于是请你写一个程序，帮助他们计算他们是否结束了游戏？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">　　输入数据第一行为两个整数</span>n<span style="">和</span>m<span style="">。</span>m<span style="">表示一共画了</span>m<span style="">条线。以后</span>m<span style="">行，每行首先有两个数字</span>(x, y)<span style="">，代表了画线的起点坐标，接着用空格隔开一个字符，假如字符是</span>"D "<span style="">，则是向下连一条边，如果是</span>"R "<span style="">就是向右连一条边。输入数据不会有重复的边且保证正确。</span><br></p><p> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">　 &nbsp;输出一行：在第几步的时候结束。假如</span>m<span style="font-family:宋体">步之后也没有结束，则输出一行“</span>draw<span style="font-family:宋体">”。</span> </p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><br></p><p>    3 5</p><p>　　1 1 D</p><p>　　1 1 R</p><p>　　1 2 D</p><p>　　2 1 R</p><p>　　2 2 D</p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>    4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见上<br></p>
</div>
</div>