<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">一天，非非正在一个n*m的森林里玩耍。</span></p><p style=""><span style="">它在第0秒从起点出发，每过一秒可以移动到上下左右四个相邻格子中的一个，现在它希望尽早走到终点。</span></p><p><span style=""> </span></p><p style=""><span style="">对于棋盘的描述：</span></p><p style=""><span style="">“_” - 空地</span></p><p style=""><span style="">“#” - 粪坑，即不能移动到该格子</span></p><p style=""><span style="">“*” - 泥潭，移动上去之后会在原地停留1s</span></p><p style=""><span style="">“O” - 起点</span></p><p style=""><span style="">“X” - 终点</span></p><p><span style=""> </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行两个数n、m。</span></p><p style=""><span style="">接下来n行，每行一个长m的字符串。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:黑体">若无法到达终点，输出“T_T”。</span></p><p style="text-indent:28px"><span style="font-family:黑体">否则，输出一个数字，表示最早在第多少秒到达终点。</span></p><p><span style="font-family:黑体">&nbsp;</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 3</span></p><p><span style="">O#X</span></p><p><span style="">*#*</span></p><p><span style="">_*_</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">9</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">1</span><span style="">≤n、m≤1000。</span></p><p><span style="">移动过程是：下、停、下、右、停、右、上、停、上，一共花费9秒。</span></p><p><br></p>
</div>
</div>