<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>栋栋有一个凸多面体形状的漂亮盒子，这个盒子的每个面都由形状为凸多边</p>
<p>形的透明玻璃薄壁组成。</p>
<p>每隔一段时间，栋栋就要使用一个激光发射器给他的盒子杀菌。激光发射器</p>
<p>能发射出一束激光，当激光照射到盒子的玻璃薄壁时，会把薄壁内外两面的细菌</p>
<p>杀死，同时有大量光线透射过玻璃，少量光线被玻璃反射。透射过玻璃的光线沿</p>
<p>原方向前进，反射的光线遵循光线的镜面反射定理，即在反射时反射光线、入射</p>
<p>光线和镜面的法线在同一平面内，反射光线与入射光线分居法线两侧，反射角（反</p>
<p>射光线与法线的夹角）等于入射角（入射光线与法线的夹角）。</p>
<p>我们认为激光被玻璃反射 k 次后的能量不足以杀死细菌（即使有多个这样的</p>
<p>光线同时照射在玻璃薄壁上也不能杀死细菌），而 k 次反射前激光照射到的细菌</p>
<p>都会被杀死。</p>
<p>激光发射器的发射口是三角形的，当发射激光时，整个发射口都会发出激光。</p>
<p>给定盒子和激光发射器的位置，栋栋想知道，盒子的玻璃薄壁上有多大面积</p>
<p>的细菌被杀死了。由于盒子的内外两面的细菌必然是同时被杀死或者同时不被杀</p>
<p>死，所以只要算出外面被杀死的细菌面积即可。</p>
<p>注意，激光或经过反射的激光可能与某些表面平行，但本题的数据保证激光</p>
<p>或经过反射的激光不会照射到与之平行的表面。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每个输入数据满足下面的输入格式，每两个数之间用一个空格隔开：</p>
<p>   输入的第一行包含三个整数 n, m, k，分别表示盒子的顶点数、盒子的面数和</p>
<p>光线的反射次数。</p>
<p>   接下来 n 行，第 i 行包含三个实数 xi, yi, zi，表示盒子第 i 个顶点的坐标。</p>
<p>   接下来 m 行，每行描述盒子的一个表面，每行第一个数 tj，表示该表面的多</p>
<p>边形的顶点个数，接下来 tj 个整数，表示这 tj 个顶点对应的盒子顶点的编号，这</p>
<p>些编号按顶点在面上的顺时针或逆时针顺序给出。</p>
<p>   接下来三行，每行 3 个整数 x, y, z，分别表示激光发射器发射口的坐标。</p>
<p>   接下来 1 行，包含 3 个整数 Δx, Δy, Δz，表示出射光线的方向是沿着向量(Δx,</p>
<p>Δy, Δz)的方向。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">每个输出文件包含一个实数，四舍五入保留两位小数，</p>
<p class="p0">表示被杀死的细菌的面积。当一个表面被多次照射到时，这个表面的面积只计算</p>
<p class="p0">一次。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>8 6 1<br>0.0 0.0 0.0<br>0.0 0.0 1.0<br>0.0 1.0 1.0<br>0.0 1.0 0.0<br>1.0 0.0 0.0<br>1.0 0.0 1.0<br>1.0 1.0 1.0<br>1.0 1.0 0.0<br>4 2 3 7 6<br>4 5 6 7 8<br>4 1 2 3 4<br>4 1 2 6 5<br>4 4 3 7 8<br>4 1 4 8 5<br>2.0 0.33 0.25<br>2.0 0.67 0.25<br>2.0 0.33 0.75<br>-1.0 0.0 0.0</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例数据如下图所示，盒子是一个正方体的形状，激光从右边照射过来，照</p>
<p>射到右侧面上，并透射过右侧面照射到左侧面上，将左右两侧面上的两个三角形</p>
<p>区域的细菌杀死。在照射到左右侧面后激光都会发生反射，但由于 k=1，反射光</p>
<p>线已不能将细菌杀死，所以不用考虑。</p>
</div>
</div>