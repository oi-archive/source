# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">有一个球形空间产生器能够在n维空间中产生一个坚硬的球体。现在，你被困在了这个n维球体中，你只知道球面上n+1个点的坐标，你需要以最快的速度确定这个n维球体的球心坐标，以便于摧毁这个球形空间产生器。 </span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">第一行是一个整数，n。接下来的n+1行，每行有n个实数，表示球面上一点的n维坐标。每一个实数精确到小数点后6位，且其绝对值都不超过20000。 </span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">有且只有一行，依次给出球心的n维坐标（n个实数），两个实数之间用一个空格隔开。每个实数精确到小数点后3位。数据保证有解。你的答案必须和标准输出一模一样才能够得分。 </span> 
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>2
  0.0 0.0
  -1.0 1.0
  1.0 0.0</pre>
<h3>
【样例输出】
</h3>
<pre>0.500 1.500</pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<br/>
</p>
<p>
<span style="font-size:medium;">数据规模：<br/>
<br/>
对于40%的数据，1&lt;=n&lt;=3<br/>
<br/>
对于100%的数据，1&lt;=n&lt;=10<br/>
<br/>
提示：给出两个定义：<br/>
<br/>
1、 球心：到球面上任意一点距离都相等的点。<br/>
<br/>
2、 距离：设两个n为空间上的点A, B的坐标为(a1, a2, …, an), (b1, b2, …, bn)，则AB的距离定义为：dist = sqrt( (a1-b1)^2 + (a2-b2)^2 + … + (an-bn)^2 )</span> 
</p>
<p>
<br/>
</p>
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search="></a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=1013">耒阳大世界（衡阳八中） OJ 1013</a>
