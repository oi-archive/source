<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>两个d<span style="">维向量A=[a1,a2,...,ad]与B=[b1,b2,...,bd]的内积为其相对应维度的权值的乘积和，即：</span></p>
<p>(a,b)=∑(i=1..d)aibi=a1b1+a2b2++adbd</p>
<p>现有n个d维向量x1,...,xn<span>，小喵喵想知道是否存在两个向量的内积为k的倍数。请帮助她解决这个问题。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件meow.in的第一行包含3个正整数n,d,k，分别表示向量的个数，维数以及待检测的倍数。<br>接下来n行每行有d个非负整数，其中第i行的第j个整数表示向量xi的第j维权值xi,j。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件meow.out包含两个整数，用空格隔开。<br />如果存在两个向量xp,xq的内积为k的整数倍，则输出两个向量的编号p与q（要求p&lt;q）。如果存在多<br />组这样的向量组合，输出其中任意一组即可。<br />若不存在这样的向量组合，则输出两个-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 5 2<br>1 0 1 0 1<br>1 1 0 1 0<br>0 1 0 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例说明</p>
<p>(x1,x2 )=1<br>(x1,x3 )=1<br>(x2,x3 )=1</p>
<p>【数据范围】</p>
<p>对于1个测试点n=2,d=20,k=2,xi,j&lt;=10</p>
<p>对于2个测试点n=5,d=20,k=2,xi,j&lt;=10</p>
<p>对于3个测试点n=10,d=20,k=3,xi,j&lt;=10</p>
<p>对于4个测试点n=20,d=20,k=2,xi,j&lt;=100</p>
<p>对于5个测试点n=50,d=20,k=3,xi,j&lt;=100</p>
<p>对于6个测试点n=50,d=50,k=2,xi,j&lt;=1000</p>
<p>对于7个测试点n=50,d=50,k=3,xi,j&lt;=3000000</p>
<p>对于8个测试点n=80,d=80,k=2,xi,j&lt;=2000000</p>
<p>对于9个测试点n=100,d=100,k=3,xi,j&lt;=3000000</p>
<p>对于10个测试点n=500,d=100,k=3,xi,j&lt;=3000000</p>
<p>对于11个测试点n=1000,d=100,k=2,xi,j&lt;=2000000</p>
<p>对于12个测试点n=1000,d=100,k=3,xi,j&lt;=3000000</p>
<p>对于13个测试点n=10000,d=100,k=2,xi,j&lt;=10</p>
<p>对于14个测试点n=10000,d=100,k=3,xi,j&lt;=10</p>
<p>对于15个测试点n=15000,d=100,k=2,xi,j&lt;=10</p>
<p>对于16个测试点n=18000,d=100,k=2,xi,j&lt;=10</p>
<p>对于17个测试点n=20000,d=100,k=2,xi,j&lt;=10</p>
<p>对于18个测试点n=50000,d=30,k=3,xi,j&lt;=10</p>
<p>对于19个测试点n=80000,d=30,k=3,xi,j&lt;=10</p>
<p>对于20个测试点n=100000,d=30,k=3,xi,j&lt;=10</p>
</div>
</div>