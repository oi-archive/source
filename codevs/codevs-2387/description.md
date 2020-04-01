<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个二维平面初始时为空，有一串往平面中加入点的命令。</p>
<p>加入的点有两种，这里称为A类点和B类点（如图1，黑色正方形表示A类点，小圆黑点表示B类点）。A类点一定位于X轴上，而且不会重叠，而B类点可以出现在平面上的任何一个位置，可以重叠。每个B类点有一个权值W。</p>
<p>处理：一、最初，将相邻两个A类点之间连一个与X轴成45度的正方形（如图2）。二、每次可以将任意两个有公共点的正方形合并为一个大正方形，合并之后两个小正方形消失。图2的左数第2、3的正方形合并后在图3中表示为灰边正方形。</p>
<p>合并后的正方形将平面划分为9个区域，与正方形4条边相邻的4个区域分别为图3中的I，II，III，IV。落在区域I中的B类点的权值和记为<em>w</em><sub>1</sub>，落在区域II中的B类点的权值和记为<em>w</em><sub>2</sub>，落在区域III中的B类点的权值和记为<em>w</em><sub>3</sub>，落在区域IV中的B类点的权值和记为<em>w</em><sub>4</sub>。落在灰色正方形内部的B类点的权值和记为<em>w</em><sub>5</sub>（B类点保证不会出现在任何一个区域的边界上），则合并费用为1<em>w</em><sub>1</sub>+2<em>w</em><sub>2</sub>+3<em>w</em><sub>3</sub>+4<em>w</em><sub>4</sub>+5<em>w</em><sub>5</sub>。落在其他区域的B类点不予考虑。每次合并之后并不影响B类点在平面上的位置和它自己所拥有的权值。</p>
<p>    每进行一次合并，由A类点形成的正方形会减少一个，直到只剩下一个正方形为止。合并总费用为每次合并费用之和。不同合并顺序的合并费用可能会不同。</p>
<p>    点是一个一个加入到平面的。加入第<em>i</em>个A类点后，平面上有<em>i</em>个A类点和在此之前加入的所有B类点。设此时的<strong><span style="text-decoration: underline;">最小</span></strong>合并费用为<em>f</em>(<em>i</em>)。</p>
<p>    给定费用限制<em>L</em>，编程求出A类点的最大数目<em>K</em>，使得<strong><span style="text-decoration: underline;">前</span></strong><strong><em><span style="text-decoration: underline;">K</span></em></strong><strong><span style="text-decoration: underline;">个</span></strong><strong><span style="text-decoration: underline;">A</span></strong><strong><span style="text-decoration: underline;">类点</span></strong>的最小合并费用不超过<em>L</em>，即<em>f</em>(<em>K</em>)&lt;=<em>L</em>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个数<em>M</em>，<em>L</em>，表示有<em>M</em>条加入点的命令，费用限制为<em>L</em>。以下包含<em>M</em>行，每行一个字母表示点的类型。“A”表示A类点，“B”表示B类点。对于A类点，后面一个数表示这个点的<em>X</em>坐标；对于B类点，后面三个数表示这个点的<em>X</em>，<em>Y</em>坐标和这个点的权值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅包含一个整数<em>K<sub>max</sub></em>，即使<em>f</em>(<em>K</em>)&lt;=<em>L</em>的最大<em>K</em>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 30.0</p>
<p>A -2</p>
<p>A 0</p>
<p>B 7 8 5.0</p>
<p>B 4 -3 2.0</p>
<p>B -3 4 1.0</p>
<p>A 2</p>
<p>B -4 5 1.0</p>
<p>A 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=A类点的数目&lt;=30000</p>
<p>5&lt;=<em>M</em>&lt;=100000</p>
<p><em>X</em>，<em>Y</em>均为整数，绝对值不超过10000000</p>
<p><em>L</em>, <em>W</em>均为实数，0&lt;<em>W</em>&lt;=10000，<em>L</em>&lt;=10<sup>11</sup>，所有输入实数最多保留三位小数</p>
<p>50%的数据满足<em>M</em>&lt;=3000</p>
<p> </p>
<p> </p>
</div>
</div>