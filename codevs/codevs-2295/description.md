<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　A君近日为准备省队选拔，特意进行了数据结构的专项训练。训练过程中就遇到了“矩形面积并”这道经典问题，即：给出N个各边与坐标轴平行(垂直)的矩形，求矩形覆盖的面积之和。A君按纵坐标建立线段树后按横坐标扫描计算，轻易AC了这道题，时间复杂度为O(NlogN)。</p>
<p>　　为了强化训练，A君将问题推广到三维空间中，即：给出N个各棱与坐标轴平行(垂直)的立方体，求立方体覆盖的体积之和。为了简化问题，令立方体均退化为正立方体，用四元组(x, y, z, r)表示一个立方体，其中x, y, z为立方体的中心点坐标，r为中心点到立方体各个面的距离(即立方体高的一半)。</p>
<p>　　这次可难住了A君，只好请你——未来的金牌——来帮助他了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行是一个正整数N。</p>
<p>　　以下N行每行四个整数x, y, z, r，由空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　共一个数，即覆盖的总体积。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>0 0 0 3</p>
<p>1 –1 0 1</p>
<p>19 3 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1944</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30% 的数据，1≤N≤5</p>
<p>对于 70% 的数据，1≤N≤30</p>
<p>对于 100% 的数据，1≤N≤100</p>
<p>对于 100% 的数据，-1000≤x, y, z≤1000，1≤r≤200</p>
</div>
</div>