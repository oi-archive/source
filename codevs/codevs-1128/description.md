<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>经过11 年的韬光养晦，某国研发出了一种新的导弹拦截系统，凡是与它的距离不超过其工作半径的导弹都能够被它成功拦截。当工作半径为0 时，则能够拦截与它位置恰好相同的导弹。但该导弹拦截系统也存在这样的缺陷：每套系统每天只能设定一次工作半径。而当天的使用代价，就是所有系统工作半径的平方和。<br>某天，雷达捕捉到敌国的导弹来袭。由于该系统尚处于试验阶段，所以只有两套系统投入工作。如果现在的要求是拦截所有的导弹，请计算这一天的最小使用代价。</p>
<p>数据范围<br>对于10%的数据，N = 1<br>对于20%的数据，1 ≤ N ≤ 2<br>对于40%的数据，1 ≤ N ≤ 100<br>对于70%的数据，1 ≤ N ≤ 1000<br>对于100%的数据，1 ≤ N ≤ 100000，且所有坐标分量的绝对值都不超过1000。<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含4 个整数x1、y1、x2、y2，每两个整数之间用一个空格隔开，表示这两套导弹拦截系统的坐标分别为(x1, y1)、(x2, y2)。<br>第二行包含1 个整数N，表示有N 颗导弹。接下来N 行，每行两个整数x、y，中间用一个空格隔开，表示一颗导弹的坐标(x, y)。不同导弹的坐标可能相同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，包含一个整数，即当天的最小使用代价。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>0 0 10 0<br>2<br>-3 3<br>10 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>两个点(x1, y1)、(x2, y2)之间距离的平方是(x1− x2)^2+(y1−y2)^2。<br>两套系统工作半径r1、r2 的平方和，是指r1、r2 分别取平方后再求和，即r1^2+r2^2。</p>
<p> </p>
</div>
</div>