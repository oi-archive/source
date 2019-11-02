<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><br></p><p>小K是一个海港的海关工作人员，每天都有许多船只到达海港，船上通常有很多来自不同国家的乘客。</p><p>小K对这些到达海港的船只非常感兴趣，他按照时间记录下了到达海港的每一艘船只情况；对于第i艘到达的船，他记录了这艘船到达的时间ti (单位：秒)，船上的乘 客数星ki，以及每名乘客的国籍 x(i,1), x(i,2),…，x(i,k);。</p><p>小K统计了n艘船的信息，希望你帮忙计算出以每一艘船到达时间为止的24小时(24小时=86400秒）内所有乘船到达的乘客来自多少个不同的国家。</p><p>形式化地讲，你需要计算n条信息。对于输出的第i条信息，你需要统计满足 ti - 86400 &lt; tp &lt;= ti的船只p，在所有的x(p,j)中，总共有多少个不同的数。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入一个正整数n，表示小K统计了 n艘船的信息。</p><p>接下来n行，每行描述一艘船的信息：前两个整数ti和ki分别表示这艘船到达海港的时间和船上的乘客数量，接下来ki个整数x(i,j)表示船上乘客的国7。</p><p>保证输入的ti是递增的，单位是秒；表示从小K第一次上班开始计时，这艘船在第 ti 秒到达海港。</p><p>保证 <img src="http://latex.codecogs.com/gif.latex?1 \le n \le 10^5">，<img src="http://latex.codecogs.com/gif.latex?\sum{ki} \le 3*10^5"> ，<img src="http://latex.codecogs.com/gif.latex?1\le x(i,j) \le 10^5">， <img src="http://latex.codecogs.com/gif.latex?1 \le t(i-1)\le  ti    \le  10^9">。</p><p>其中<img src="/source/codevs/codevs-5621/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHN1bXtraX0=.latex">表示所有的ki的和。</p><p><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出n行，第i行输出一个整数表示第i艘船到达后的统计信息。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>1 4 4 1 2 2<br>2 2 2 3</p><p>10 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br>4<br>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><img src="/source/codevs/codevs-5621/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01NjIxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2VfMjAxNjExMjYyMDA3MzJfMTcyLnBuZw==.png" title=""></p>
</div>
</div>