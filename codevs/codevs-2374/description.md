<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>魔法师栋栋有一个美丽的魔幻花园，在花园里，栋栋种满各式各样的魔幻植物，花园里一年四季都开满着姹紫嫣红的鲜花。栋栋的朋友们都特别喜欢来花园里玩。 <br>花园的浇灌系统是由栋栋特别设计的，栋栋用魔法在花园上空变出了 n 个喷头，这些喷头都连接着附<br>近的圣水河。浇灌的时候，所有的喷头一起喷出一道道水流，水流在空中划出一道道美丽的弧线，最终正好浇灌到n棵最缺水的魔幻植物上。 <br>栋栋把每个喷头都设在同一水平高度h。所有的喷头都是水平放置的，当水流从喷头喷出时，只有水平的速度(每个喷头的水平速度不一定相同)。 魔幻花园里没有风，空气阻力可以忽略。所以在重力的影响下(魔幻花园的重力加速度为 g)，水流的轨迹是一条完美的抛物线。空间上的任意点都最多被三个喷头喷到，两条水流相交不会影响各自的轨迹。 <br>近些年来魔幻花园附件新建了许多工厂，圣水河受到了污染，栋栋不想受污染的水影响到他的花园，所以他要使用魔法先净化一下浇灌的水。栋栋的魔法只能净化从喷头喷出来的水，他可以施魔法在空中的一个水平面形成一个凸多边形的滤水层，所有通过滤水层的水都会被净化，施这个魔法需要的能量和滤水层的面积成正比，每平方米滤水层需要 1单位的魔法能量。栋栋想净化所有的水，他最少需要多少能量呢？ <br>为了更好的描述问题，栋栋在花园建立起了一个三维的直角坐标系，以花园的西北角为坐标轴的原点，从原点向东是 x轴的正方向，向南是y轴的正方向，向上是 z 轴的正方向。这样第 i 个喷头的位置可以用(xi,yi,h)来表示，而第 j 棵魔幻植物的位置可以用(xj’,yj’,0)来表示。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 第一行为两个实数 h, g，表示喷头的高度和魔幻花园的重力加速度。第二行为整数 n，表示有多少个喷头。 <br>接下来 n行，每行四个整数 xi, yi, xi’, yi’，整数间使用一个空格分隔。表示第i 个喷头的坐标是(xi, yi, h)，它喷出的水正好浇灌到了(xi’, yi’, 0)位置的魔幻植物上。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅有一个实数，表示栋栋最少需要的能量，精确到小数点后3位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 9.8 <br>3 <br>0 0 0 0 <br>1 0 100 0 <br>0 50 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>25.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20%的数据，1≤ n ≤10 <br>对于 50%的数据，1≤ n ≤50 <br>对于 100%的数据，1≤n ≤100 <br>0 &lt; h ≤ 10000.0 <br>0 &lt; g ≤ 100.0 <br>0 ≤ xi, yi, xi’, yi’ ≤ 1000</p>
</div>
</div>