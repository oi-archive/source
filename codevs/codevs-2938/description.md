<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【迷宫描述】 </p>
<p>      迷宫符号表示：</p>
<p>l         . 代表可以通行的区域</p>
<p>l         4个方向的激光发射器</p>
<p>^ 向上发射激光</p>
<p>v 向下发射激光</p>
<p>&gt; 向右发射激光</p>
<p>&lt; 向左发射激光</p>
<p>(注意: v为小写字母)</p>
<p>l         2种角度的双面镜子</p>
<p>/  \  可以按照符号的角度呈90度反射光线</p>
<p>l         障碍物</p>
<p>#  不可通行，光线不能通过</p>
<p>l         初始点：大写字母S；终点：大写字母E（各1个）</p>
<p> </p>
<p>迷宫状况：</p>
<p>1、  激光碰到了边界、激光器、障碍物就会停止；</p>
<p>2、  你可以在任意时候使用遥控器旋转任意一个镜子到另一种角度，花费1单位时间；</p>
<p>3、  你可以在1单位时间内移动上、下、左或右1格；</p>
<p>4、  你不能移出边界、也不能移动到有镜子、激光器、障碍物占据的地方；</p>
<p>5、  你不可以被激光器发出的激光射中。</p>
<p> </p>
<p>现在请求出从起点到终点的最短时间消耗。.</p>
<p>相信大家玩过带有镜子和激光发射器的迷宫游戏，游戏的核心就是如何通过调整镜子的角度，避开所有激光束，以最短的步长，安全地到达终点。</p>
<p>现在你正处于在一个n*m的迷宫里，该迷宫有障碍物、激光发射器和双面镜子。虽然你没有武器，不能毁掉迷宫中的激光发射器、镜子或者障碍物，但是你手上有遥控器，可以随时更改迷宫中任何一个镜子的角度，现在就看你是否能凭着这个遥控器，安全地逃出生天了。<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为整数n,m(2&lt;n,m&lt;=10)，接着n行，每行m个字符，表示迷宫</p>
<p>输入数据的迷宫的镜子数不会超过5个，初始状态下起始点所在位置是安全的，并且保证肯定有办法可以走到终点。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，代表从起点到达终点的最短时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5<br>S.v..<br>.....<br>.....<br>../..<br>....E<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>(2&lt;n,m&lt;=10)，</p>
</div>
</div>