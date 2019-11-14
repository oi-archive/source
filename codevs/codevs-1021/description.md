<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>麦克找了个新女朋友，玛丽卡对他非常恼火并伺机报复。</p>
<p>    因为她和他们不住在同一个城市，因此她开始准备她的长途旅行。</p>
<p>    在这个国家中每两个城市之间最多只有一条路相通，并且我们知道从一个城市到另一个城市路上所需花费的时间。</p>
<p>    麦克在车中无意中听到有一条路正在维修，并且那儿正堵车，但没听清楚到底是哪一条路。无论哪一条路正在维修，从玛丽卡所在的城市都能到达麦克所在的城市。</p>
<p>    玛丽卡将只从不堵车的路上通过，并且她将按最短路线行车。麦克希望知道在最糟糕的情况下玛丽卡到达他所在的城市需要多长时间，这样他就能保证他的女朋友离开该城市足够远。</p>
<p>编写程序，帮助麦克找出玛丽卡按最短路线通过不堵车道路到达他所在城市所需的最长时间(用分钟表示)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个用空格隔开的数N和M，分别表示城市的数量以及城市间道路的数量。1≤N≤1000，1≤M≤N*(N-1)/2。城市用数字1至N标识，麦克在城市1中，玛丽卡在城市N中。</p>
<p>接下来的M行中每行包含三个用空格隔开的数A，B和V。其中1≤A，B≤N，1≤V≤1000。这些数字表示在A和城市B中间有一条双行道，并且在V分钟内是就能通过。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;输出文件的第一行中写出用分钟表示的最长时间，在这段时间中，无论哪条路在堵车，玛丽卡应该能够到达麦克处，如果少于这个时间的话，则必定存在一条路，该条路一旦堵车，玛丽卡就不能够赶到麦克处。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 7</p>
<p>1 2 8</p>
<p>1 4 10</p>
<p>2 3 9</p>
<p>2 4 10</p>
<p>2 5 1</p>
<p>3 4 7</p>
<p>3 5 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>27</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>