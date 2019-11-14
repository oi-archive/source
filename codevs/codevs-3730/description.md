<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">随着智能手机的日益普及，人们对无线网的需求日益增大。某城市决定对城市内的公共场所覆盖无线网。</span></p><p style=""><span style="">假设该城市的布局为由严格平行的129条东西向街道和129条南北向街道所形成的网格状，并且相邻的平行街道之间的距离都是恒定值1。东西向街道从北到南依次编号为0,1,2…128,南北向街道从西到东依次编号为0,1,2…128。</span></p><p style=""><span style="">东西向街道和南北向街道相交形成路口，规定编号为x的南北向街道和编号为y的东西向街道形成的路口的坐标是（x, y）。 在 某 些 路 口 存 在 一 定 数 量 的 公 共 场 所 。</span></p><p style=""><span style="">由于政府财政问题，只能安装一个大型无线网络发射器。该无线网络发射器的传播范围是一个以该点为中心，边长为2*d的正方形。传播范围包括正方形边界。</span></p><p style=""><span style="">例如下图是一个d = 1的无线网络发射器的覆盖范围示意图。</span></p><p style=""><br></p><p><br></p><p>  <img height="245" src="/source/codevs/codevs-3730/img/aHR0cDovL3d3dy5qb3lvaS5jbi9tZWRpYS9ibG9iXzIwMTUwNTAyMTcwMTE1XzM0NC5wbmc=.png" style="" title="" width="670"></p><p><span style="">   现在政府有关部门准备安装一个传播参数为d的无线网络发射器，希望你帮助他们在城市内找出合适的安装地点，使得覆盖的公共场所最多。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入文件名为wireless.in。</span></p><p style=""><span style="">第一行包含一个整数d，表示无线网络发射器的传播距离。</span></p><p style=""><span style="">第二行包含一个整数n，表示有公共场所的路口数目。</span></p><p style=""><span style="">接下来n行，每行给出三个整数x, y, k,  中间用一个空格隔开，分别代表路口的坐标(x, y)以及该路口公共场所的数量。同一坐标只会给出一次。</span></p><p><span style=""> </span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style=";font-family:宋体;font-size:14px">输出文件名为wireless.out。</span></p><p style="text-indent: 28px;"><span style=";font-family:宋体;font-size:14px">输出一行，包含两个整数，用一个空格隔开，分别表示能覆盖最多公共场所的安装地点方案数，以及能覆盖的最多公共场所的数量。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table width="553"><tbody><tr><td style="" valign="top" width="277"><p style=""><span style="">wireless.in</span></p></td><td style="" valign="top" width="277"><p style=""><span style="">wireless.out</span></p></td></tr><tr style=""><td style="" valign="top" width="277"><p><span style="">1</span></p><p><span style="">2</span></p><p><span style="">4 4 10</span></p><p><span style="">6 6 20</span></p></td><td style="" valign="top" width="277"><p><span style="">1 30</span></p></td></tr></tbody></table><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>见上。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于100%的数据，1 ≤ d ≤ 20，1 ≤ n ≤  20， 0 ≤ x ≤ 128, 0 ≤ y ≤  128, 0 &lt;</span><span style=""> </span><span style="">k ≤ 1,000,000。</span></p><p><br></p>
</div>
</div>