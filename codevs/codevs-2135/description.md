<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这是一个单人游戏。</p>
<p>游戏开始时，玩家控制的人物出生在迷宫的某个位置，玩家的目标是控制人物走到迷宫的某个出口（出口可能有多个）。迷宫里有K 类陷阱（用“A”、“B”、“C”……表示，相同字母代表相同类型的陷阱），每类陷阱可能是有害的或无害的，而在游戏开始时玩家并不知道哪些陷阱是有害的，哪些是无害的。同一类陷阱的状态相同，即用同一个字母标志的陷阱要么全部有害，要么全部无害，不会发生一部分有害而另一部分无害的情况。任何陷阱状态的组合都有一个发生概率，考虑下例：</p>
<p>当k=2 时，迷宫内共有两类陷阱，分别用“A”和“B”表示，陷阱状态的组合共有4种：</p>
<p>1、“A”是无害陷阱，“B”是无害陷阱。</p>
<p>2、“A”是有害陷阱，“B”是无害陷阱；</p>
<p>3、“A”是无害陷阱，“B”是有害陷阱；</p>
<p>4、“A”是有害陷阱，“B”是有害陷阱；</p>
<p>下面给出了一个合法的概率表格：</p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="189">
<p> </p>
</td>
<td valign="top" width="189">
<p>“A”是无害陷阱</p>
</td>
<td valign="top" width="189">
<p>“A”是有害陷阱</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>“B”是无害陷阱</p>
</td>
<td valign="top" width="189">
<p>36%</p>
</td>
<td valign="top" width="189">
<p>24%</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>“B”是有害陷阱</p>
</td>
<td valign="top" width="189">
<p>24%</p>
</td>
<td valign="top" width="189">
<p>16%</p>
</td>
</tr>
</tbody>
</table>
</div>
<p>当K=3 时，会有8种不同的陷阱状态组合，如果我们依然坚持使用概率表格，那么这个表格将会是三维的（2*2*2 ，每一维对应着一类陷阱）。当K&gt;=3时，这将使得题目难以描述。因此我们使用一个大小为 2^k的数组p 来描述每种情况发生的可能性， p的下标范围为0~2^k-1 。</p>
<p>p是这样生成的：</p>
<p>对于每个可能的陷阱状态组合，考虑所有 类陷阱，令1表示某个陷阱有害，0表示某个陷阱无害，把“A”作为二进制数的第0位（从右边开始计数），“B”作为第1位，“C”作为第2位……通过以上操作，我们可以得到一个<em>K</em>位的二进制数，把它转化成十进制后， 2^k种陷阱状态的组合将会与整数0~2^k-1 一一对应。</p>
<p>定义 s表示p 中所有元素和，即：</p>
<p> </p>
<p>则陷阱状态组合 i出现的概率为pi/s 。上述表格对应的一个合法数组 p是：</p>
<p> p0=36 p1=24 p2=24 p3=16</p>
<p> </p>
<p>当然同一个概率表格可能会对应多个数组 p（事实上有无数个数组 能够迎合表格数据），例如上述表格同时也对应着下面的数组 p：</p>
<p> p0=72 p1=48 p2=48 p3=32</p>
<p> </p>
<p>玩家控制的人物初始情况下有H点生命，当人物踏上某个陷阱时，如果这个陷阱是有害的，那么会损失1点生命，否则这个陷阱是无害的，不损失生命。无论上述哪种情况发生，玩家会立刻得到这个陷阱的信息（有害或无害）。一旦生命小于等于0，玩家控制的人物会立刻死亡。</p>
<p>迷宫可以看作m*n的方格地图，每个元素可能是：</p>
<p>“.”：表示这是平地，可以通过；</p>
<p>“#”：表示这是墙，不能通过；</p>
<p>“A”，“B”，“C”……：表示这是一个陷阱；</p>
<p>“$”：表示这是起点，地图中有且仅有一个；</p>
<p>“@”：表示这是终点，地图中可以有多个，也可以一个也没有。</p>
<p>人物可以向上下左右四个方向行走，不可以走对角线，也不可以走出地图。</p>
<p>给定m*n 的地图K、H 、 以及大小为 2^k的概率数组。你的任务是求出在执行最优策略时，人物能活着走出迷宫的概率。</p>

<img src="/source/codevs/codevs-2135/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMTM1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NzE2MzA5OS44ODAuMTEzNjQ3MjE5OTYxLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含4个整数，分别表示 m n K H；</p>
<p>下面 m行每行 n个字符描述迷宫地图；</p>
<p>最后一行包含 2^k个非负整数描述数组 p，数组下标从0开始。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="NOI">仅包含一个数字，表示在执行最优策略时，人物活着走出迷宫的概率。四舍五入保留3位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 3 2 1</span></p>
<p><span>.$.</span></p>
<p><span>A#B</span></p>
<p><span>A#B</span></p>
<p><span>.@.</span></p>
<p><span>30 30 20 20</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>0.600</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top" width="27%">
<p>测试点编号</p>
</td>
<td valign="top" width="17%"> </td>
<td valign="top" width="17%"> </td>
<td valign="top" width="18%"> </td>
<td valign="top" width="18%"> </td>
</tr>
<tr>
<td valign="top" width="27%">
<p>1</p>
</td>
<td valign="top" width="17%">
<p>29</p>
</td>
<td valign="top" width="17%">
<p>28</p>
</td>
<td valign="top" width="18%">
<p>5</p>
</td>
<td valign="top" width="18%">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>2</p>
</td>
<td valign="top" width="17%">
<p>28</p>
</td>
<td valign="top" width="17%">
<p>20</p>
</td>
<td valign="top" width="18%">
<p>4</p>
</td>
<td valign="top" width="18%">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>3</p>
</td>
<td valign="top" width="17%">
<p>25</p>
</td>
<td valign="top" width="17%">
<p>30</p>
</td>
<td valign="top" width="18%">
<p>1</p>
</td>
<td valign="top" width="18%">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>4</p>
</td>
<td valign="top" width="17%">
<p>25</p>
</td>
<td valign="top" width="17%">
<p>30</p>
</td>
<td valign="top" width="18%">
<p>1</p>
</td>
<td valign="top" width="18%">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>5</p>
</td>
<td valign="top" width="17%">
<p>25</p>
</td>
<td valign="top" width="17%">
<p>30</p>
</td>
<td valign="top" width="18%">
<p>1</p>
</td>
<td valign="top" width="18%">
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>6</p>
</td>
<td valign="top" width="17%">
<p>5</p>
</td>
<td valign="top" width="17%">
<p>5</p>
</td>
<td valign="top" width="18%">
<p>4</p>
</td>
<td valign="top" width="18%">
<p>4</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>7</p>
</td>
<td valign="top" width="17%">
<p>12</p>
</td>
<td valign="top" width="17%">
<p>11</p>
</td>
<td valign="top" width="18%">
<p>4</p>
</td>
<td valign="top" width="18%">
<p>5</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>8</p>
</td>
<td valign="top" width="17%">
<p>19</p>
</td>
<td valign="top" width="17%">
<p>17</p>
</td>
<td valign="top" width="18%">
<p>5</p>
</td>
<td valign="top" width="18%">
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>9</p>
</td>
<td valign="top" width="17%">
<p>23</p>
</td>
<td valign="top" width="17%">
<p>25</p>
</td>
<td valign="top" width="18%">
<p>5</p>
</td>
<td valign="top" width="18%">
<p>4</p>
</td>
</tr>
<tr>
<td valign="top" width="27%">
<p>10</p>
</td>
<td valign="top" width="17%">
<p>30</p>
</td>
<td valign="top" width="17%">
<p>29</p>
</td>
<td valign="top" width="18%">
<p>5</p>
</td>
<td valign="top" width="18%">
<p>5</p>
</td>
</tr>
</tbody>
</table>
</div>
</div>