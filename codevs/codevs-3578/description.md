<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">随着智能手机的日益普及，人们对无线网的需求日益增大。某城市决定对城市内的公共场所覆盖无线网。</p><p style="">假设该城市的布局为由严格平行的 129 条东西向街道和 129 条南北向街道所形成的网格状，并且相邻的平行街道之间的距离都是恒定值 1 。东西向街道从北到南依次编号为0,1,2…128,南北向街道从西到东依次编号为 0,1,2…128。</p><p style="">东西向街道和南北向街道相交形成路口，规定编号为 x 的南北向街道和编号为 y 的东西向街道形成的路口的坐标是（x, y）。在某些路口存在一定数量的公共场所。</p><p style="">由于政府财政问题，只能安装一个大型无线网络发射器。该无线网络发射器的传播范围是一个以该点为中心，边长为 2*d 的正方形。传播范围包括正方形边界。</p><p style="">例如下图是一个 d = 1 的无线网络发射器的覆盖范围示意图。</p><p style=""><span style="">现在政府有关部门准备安装一个传播参数为 d 的无线网络发射器，希望你帮助他们在城 市内找出合适的安装地点，使得覆盖的公共场所最多。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行包含一个整数 d，表示无线网络发射器的传播距离。</p><p style="">第二行包含一个整数 n，表示有公共场所的路口数目。</p><p style="">接下来 n 行，每行给出三个整数 x, y, k, 中间用一个空格隔开，分别代表路口的坐标(x, y)以及该路口公共场所的数量。同一坐标只会给出一次。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">输出一行，包含两个整数，用一个空格隔开，分别表示能覆盖最多公共场所的安装地点方案数，以及能覆盖的最多公共场所的数量。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">1</p><p style="">2</p><p style="">4 4 10</p><p style="">6 6 20</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p><p><span style="">对于 100%的数据，1 ≤ d ≤ 20，1 ≤ n ≤ 20， 0 ≤ x ≤ 128, 0 ≤ y ≤ 128, 0 &lt; k ≤ 1,000,000。</span></p><p><span style=""><br></span></p>
</div>
</div>