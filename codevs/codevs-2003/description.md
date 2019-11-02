<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　在平面直角坐标系中，Wayne需要你完成n次操作，操作只有两种：</span><br><span>　　1.0 x y。表示在坐标系中加入一个以(x, y)为圆心且过原点的圆。</span><br><span>　　2.1 x y。表示询问点(x, y)是否在所有已加入的圆的内部（含圆周），且至少在一个圆内部（含圆周）。</span><br><span>　　为了减少你的工作量，题目保证圆心严格在x轴上方（纵坐标为正），且横坐标非零。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第1行一个整数n。</span><br><span>　　接下来n行，每行第一个数是0或1，分别表示两种操作。</span><br><span>　　接着有两个实数x和y，具体意义见题面。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　对于每个询问操作，如果点在所有已加入的圆内（或圆周上），则输出&ldquo;Yes&rdquo;（不含引号）；否则输出&ldquo;No&rdquo;（不含引号）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5</span><br><span>0 2.0000 3.0000</span><br><span>0 4.0000 1.0000</span><br><span>1 1.000000 1.000000</span><br><span>0 -3.0000 2.0000</span><br><span>1 1.000000 1.000000</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>Yes</span><br><span>No</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span><img height="603" src="/source/codevs/codevs-2003/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9N0FlTXk5eWc=.do" width="852"></span></p>
<p><span>　　如图，第一次询问时圆D并未加入，E在圆B和圆C内；第二次询问时E不在圆D内。</span></p>
<p><span><br></span></p>
<p><span><span>　　对于30%的数据，n≤1000；</span><br><span>　　对于40%的数据，输入数据可看作是不相关的随机数；</span><br><span>　　对于另外20%的数据，n≤100000，圆的交区域不会由多于20条圆弧组成；</span><br><span>　　对于另外20%的数据，第一次出现查询操作后不再加圆；</span><br><span>　　对于100%的数据，n≤500000，所有坐标绝对值不超过10000。</span><br><span>　　输入数据保证圆心纵坐标为正，横坐标非零。</span><br><span>　　圆心坐标保留4位小数，询问点坐标保留6位小数，请选手注意控制精度。</span></span></p>
<p><span><span><br></span></span></p>
<p><span><span>来源：<span>中国国家队清华集训 2012-2013 第二天</span></span></span></p>
</div>
</div>