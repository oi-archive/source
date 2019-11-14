<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>2300年，人类的科技高度发达，人口急剧膨胀。地球已经不能满足人类的需要，</p><p>所以科学家们正在寻找在宇宙中居住的方法。找到合适的居住环境是一大难题，因为</p><p>宇宙中充满着各种各样的危险，比如在某个区域内经常有小行星或陨石出没（这些都</p><p>称作危险飞行物）。科学家们经过观察发现危险飞行物的飞行轨迹要么互相平行要么</p><p>互相垂直（在三维空间中）。所以可以把宇宙看作是许多等大的正方体格子所组成的</p><p>大长方体，凡是有危险飞行物经过的格子都不是理想的居住地。现在给你宇宙空间的</p><p>大小和危险飞行物的飞行轨迹，请你编程帮助科学家们找到一个最大的理想居住地，</p><p>且这个居住地是一个正方体。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：x0,y0,z0,n</p><p>说明：x0,y0,z0是宇宙空间的大小。n是危险飞行物的个数。</p><p>以下有n行，每一行为：kind,x,y,z,t</p><p>说明：kind是一个字符只可能为"x","y","z"，表示轨迹平行于哪个坐标轴。</p><p>      x,y,z表示轨迹的起始位置，t为x,y,z中变化量的终点。</p><p>      比如：x 1 2 3 9表示轨迹从(1,2,3)到(9,2,3)。</p><p>            y 1 2 3 2表示轨迹仅为(1,2,3)。</p><p>            z 1 2 3 1表示轨迹从(1,2,3)到(1,2,1)。</p><p>注意：这里的(x,y,z)指的是坐标上的格，不是坐标点。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行：m</p><p>说明：m指那个最大的正方体的边长。若不存在理想居住地，则输出0。</p><p><br/></p><p><br/></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 10 10 3</p><p>x -10 0 0 10</p><p>y 0 -10 0 10</p><p>z 0 0 10 -10</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">限制：</p><p style="">    0&lt;=n&lt;=1000。</p><p style="">    0&lt;x0,y0,z0&lt;=50 且x0,y0,z0为整数。</p><p style="">    -x0&lt;=x&lt;=x0 ; -y0&lt;=y&lt;=y0 ; -z0&lt;=z&lt;=z0 ; 且x,y,z为整数。</p><p style="">    当kind为x时，-x0&lt;=t&lt;=x0</p><p style="">    当kind为y时，-y0&lt;=t&lt;=y0</p><p style="">    当kind为z时，-z0&lt;=t&lt;=z0</p><p style=""><br></p><p><br></p>
</div>
</div>