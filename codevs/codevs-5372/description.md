<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>   这个任务的主人公是画家QZJ，他用了很多时间来环游世界。众多的旅游景点总能给他画画的灵感，如今这些艺术品是被高度赞扬的。又一次，QZJ发现自己在一个充满摩天大楼的大都市，被这样的景色陶醉，他马上就开始了工作。QZJ只画他所能看到的摩天大楼的轮廓，这是一般程序员无法理解。不幸的是，在他完成这个杰作的一周后，这幅画着火了。</p><p>    为了重建绘画，QZJ想四面八方的人求助，建筑师提供了所有摩天大楼的精确尺寸，物理学家、数学家在忽略了空气阻力后给出了飞机上的摩天大楼俯视图，现在轮到你了。</p><p>    从你的角度来看，QZJ的摩天大楼是矩形的，边分别平行于横坐标轴和纵坐标轴。图像的横坐标部分用字符“*”表示，摩天大楼的轮廓用“#”表示，图像的其余部分用“.”表示。图像最左边的部分一定是摩天大楼边，图像的最右边一定也是摩天大楼的边。另外，为了验证数学家给出的结果，输出的周长不包括给定的横边上的轮廓。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入的第一行包括一个整数N（1≤N≤10000），表示摩天大楼的数量。</p><p>    接下来的N行把包括三个整数L，R和H（1≤L，R，H≤1000,3≤R-L≤1000），分别表示第i个摩天大楼的位置。每座摩天大楼的在直角坐标系中，被认为它是左下角（L,0），右上角（R，H）的矩形。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出的第一行包括QZJ画的大楼的轮廓周长。</p><p>&nbsp; &nbsp; 接下来的h+1行，其中h+1是最高的摩天大楼的高度，输出的图形必须按照QZJ的绘画方式。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>1 5 4</p><p>7 11 3</p><p>9 13 5</p><p><span style="font-family: monospace;"></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>28</p><p>........####</p><p>####....#..#</p><p>#..#..###..#</p><p>#..#..#....#</p><p>#..#..#....#</p><p>************</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">【数据范围】</p><p>50%的测试数据中，1≤N≤100,1≤L，R，H≤100。<br></p><p>【样例解释】<br></p><p>在第一个样例中，蓝色部分是摩天大楼的轮廓，用“#”表示，黄色的部分是Vincent为了定位画的横坐标，用“*”表示。<br></p><p><img height="332" src="/source/codevs/codevs-5372/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01MzcyL2h0dHA6Ly93d3cueXV5YW9pLmNuOjgwOC91cGxvYWQvMjAxNjA4LzEoNSkucG5n.png" style="" width="713"><br></p><p><br></p>
</div>
</div>