<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>T 公司是一家专门生产彩色珠子项链的公司，其生产的项链设计新颖、款式 多样、价格适中，广受青年人的喜爱。最近 T 公司打算推出一款项链自助生产 系统，使用该系统顾客可以自行设计心目中的美丽项链。 该项链自助生产系统包括硬件系统与软件系统，软件系统与用户进行交互并 控制硬件系统，硬件系统接受软件系统的命令生产指定的项链。该系统的硬件系 统已经完成，而软件系统尚未开发，T 公司的人找到了正在参加全国信息学竞赛 的你，你能帮助 T 公司编写一个软件模拟系统吗？ 一条项链包含 N 个珠子，每个珠子的颜色是 1, 2, …, c 中的一种。项链被固 定在一个平板上，平板的某个位置被标记位置 1，按顺时针方向其他位置被记为 2,3,…,N。 </p>
<p>你将要编写的软件系统应支持如下命令：</p>
<table border="0">
<tbody>
<tr>
<td>命令</td>
<td>参数限制</td>
<td>内容</td>
</tr>
<tr>
<td>R k</td>
<td>0&lt;k&lt;N</td>
<td>意为 Rotate k。将项链在平板上顺时针 旋转 k 个位置, 即原来处于位置 1 的珠 子将转至位置 k+1，处于位置 2 的珠子 将转至位置 k+2，依次类推。 </td>
</tr>
<tr>
<td>F</td>
<td> </td>
<td> F 意为 Flip。将平板沿着给定的对称轴翻 转，原来处于位置 1 的珠子不动，位置 2 上的珠子与位置 N 上的珠子互换，位 置 3 上的珠子与位置 N-1 上的珠子互 换，依次类推。</td>
</tr>
<tr>
<td>S i j</td>
<td>1≤i , j≤N</td>
<td>意为 Swap i , j。将位置 i 上的珠子与位 置 j 上的珠子互换。 </td>
</tr>
<tr>
<td>P i j x</td>
<td>1≤i , j≤N, x≤c </td>
<td>意为 Paint i , j , x。将位置 i 沿顺时针方 向到位置 j 的一段染为颜色 x。 </td>
</tr>
<tr>
<td>C</td>
<td> </td>
<td>意为 Count。查询当前的项链由多少个 “部分”组成，我们称项链中颜色相同 的一段为一个“部分”。 </td>
</tr>
<tr>
<td>CS i j</td>
<td>1≤i , j≤N</td>
<td>意为 CountSegment i , j。查询从位置 i 沿顺时针方向到位置 j 的一段中有多少 个部分组成</td>
</tr>
</tbody>
</table>

<img src="/source/codevs/codevs-1798/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzk4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc5OC5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行包含两个整数 N, c，分别表示项链包含的珠子数目以及颜色 数目。第二行包含 N 个整数， x1, x2…, xn，表示从位置 1 到位置 N 的珠子的颜色， 1 ≤ xi ≤ c。第三行包含一个整数 Q，表示命令数目。接下来的 Q 行每行一条命令， 如上文所述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个 C 和 CS 命令，应输出一个整数代表相应的答案。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p>
<p>1 2 3 2 1</p>
<p>4</p>
<p>C</p>
<p>R 2</p>
<p>P 5 5 2</p>
<p>CS 4 1 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>
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
<p>对于 60%的数据，N ≤ 1 000，Q ≤ 1 000；</p>
<p>对于 100%的数据，N ≤ 500 000，Q ≤ 500 000，c ≤ 1 000。 </p>
</div>
</div>