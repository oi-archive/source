<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这次我们要在一个n次函数中取一点作切线，要求输出其切线的方程</p>
<p>【切线的定义】</p>
<p> P和Q是函数图像f(x) 上邻近的两点，其中P是定点，当Q点沿着函数图像的线无限地接近P点时，那么直线PQ的就是函数 f(x) 在点P的切线，P点叫做切点。</p>
<p>例子请见下图：</p>
<p>【计算提示】</p>
<p>以 f (x) = x*x 为例子 ，现在要求过定点 P (3,9) 的切线方程</p>
<p>假设Q点位于 ( 3+k, (3+k)*(3+k) )</p>
<p>那么过 PQ 的直线的斜率为 ： </p>
<p>dY/dX = [(3+k)*(3+k) -3 *3] / (3+k-3)  =(6*k+k*k)/k=6+k</p>
<p>(dY 代表 直线沿 Y轴的增量 ，dX代表直线沿着 X轴的增量)</p>
<p>如果 PQ 是切线，那么 Q会无限接近于 P，也就是说 k 无限接近于0，也就说PQ的斜率无限接近于 6 ，因此 函数 f (x) =x*x 的斜率为6 。 然后就可以进一步求出 切线的方程为：  Y = 6X - 9</p>
<p>【函数的表示】</p>
<p>一个n次函数可以表示为</p>
<p>F(x) = a<sub>n</sub>*X<sup>n</sup>+a<sub>n-1</sub>*X<sup>n-1</sup>+a<sub>n-2</sub>*X<sup>n-2</sup>+… +a<sub>1</sub>*X + a<sub>0</sub></p>
<p>并且 a<sub>n</sub> 不为0</p>
<p>因此，我们只要知道函数的次数n，以及 a<sub>0</sub>到a<sub>n</sub> 的值，就可以唯一确定一个n次函数。</p>
<p> </p>
<p>【切线表示】</p>
<p>切线是一条直线，其方程可以表示为  G(x) =k*x+b</p>
<p>也就是说给出 k , b 的值，就可以确定一条切线方程。</p>

<img src="/source/codevs/codevs-2526/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNTI2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2ODA3ODY5Mi45NDAuMDc3MDMxMTQzNTc1MS5KUEc=.JPG" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入整数 n  (1&lt;=n&lt;=8)</p>
<p>第二行输入 n+1 个整数 ，范围在 [-10,10] 之间，用空格隔开，从左到右分别代表 a<sub>0</sub>,a<sub>1</sub> ,a<sub>2</sub>……a<sub>n </sub>，其中 a<sub>n</sub>不为0</p>
<p>第三行输入P 点的X坐标 ，范围在 [-10,10] 之间</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行包含两个整数 k ，b ，用一个空格隔开，b后面不能有空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>0 0 1</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6 -9</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入数据保证有解，并且保证最后的答案 k ,b 为整数并且其的值 位于 -10<sup>6</sup> 到 10<sup>6</sup> 之间 。</p>
</div>
</div>