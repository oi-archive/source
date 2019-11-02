<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在峰会期间，必须使用许多保镖保卫北约组织的各国代表。代表们除了由他自己的随身保镖保护外，组委会还指派了一些其他的特工和阻击手保护他们。为了使他们的工作卓有成效，使被保卫的人的安全尽可能得到保障，保镖被分配到被保护人的各个方向。</span></p><p style=""><br></p><p><span style="">保镖的最佳站立位置应该是这样的：被保护人应站在所有保镖的对称中心。但是，只要被保护人一移动，保镖就很难根据要人的新位置调整位置。大多数的特工都很难对此作出实时调整。</span></p><p style=""><span style="">因此，内政部长高斯决定将该过程逆转一下，保镖先站好自己的位置，然后要人在他们的对称中心找到合适的位置。如果要人随便走动，我们就对他的安全不必负责。</span></p><p style=""><span style="">你的工作是使这个过程自动操作。给出一组N个点（保镖的位置），你要找出它们的对称中心S，在这儿被保护人将相对安全。下面以此类推。</span></p><p style=""><span style="">首先我们给定一点A以及对称中心S，点A'是点A以S为对称中心形成的像点，即点S是线段AA'的对称中心。</span></p><p style=""><span style="">点阵组（X）以S为中心的像点是由每个点的像点组成的点阵组。X是用来产生对称中心S的，即点阵X以S为中心的像点的集合即为点阵X本身。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    <span style="">输入文件第一行是一个整数N，1&lt;=N&lt;=20000，接下来的N行每行包含用空格隔开的两个整数Xi和Yi，-100000&lt;=Xi,Yi&lt;=100000，表示这组点阵中第I个点的笛卡尔坐标值。</span></p><p style=""><span style="">因为任何两个保镖都不会站在同一个位置上，所以在给定的作业中，任何两点都不相同。但注意保镖可以站在被保护人相同的位置。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp;&nbsp;<span style="font-family: 宋体; text-indent: 28px;">输出文件仅有一行。如果给定的点阵能产生一个对称中心，则输出“V.I.P&nbsp; should&nbsp; stay&nbsp; at (x,y)”，其中X和Y代表中心的笛卡尔坐标值，格式为四舍五入保留至小数点后一位。如果该组点阵无对称中心，输出&quot;This is a dangerous situation.&quot;，注意输出时除了两个单词之间用一个空格隔开外，不要输出多余空格。</span></p><p>&gt;</p><p><br/></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">8</span></p><p><span style="">1 10</span></p><p><span style="">3 6</span></p><p><span style="">6 8</span></p><p><span style="">6 2</span></p><p><span style="">3 -4</span></p><p><span style="">1 0</span></p><p><span style="">-2 -2</span></p><p><span style="">-2 4</span></p><p><br></p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">V.I.P. should stay at (2.0,3.0).</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>上面说了</p>
</div>
</div>