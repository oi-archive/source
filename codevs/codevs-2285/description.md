<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小三的生日快到了，某部长送了她一份礼物。小三兴奋的打开了礼物盒，尼玛发现面居然还有4个盒子，好吧，那小三继续打开里面的四个盒子，TMD其中两个盒子里面还分别有两三个小盒子！</p>
<p>进入正题吧，问题只跟盒子有关，跟小三完全没关系的。</p>
<p>盒子的大小分级别：</p>
<p>一个1级的盒子最多能够装下4个0级的盒子；</p>
<p>一个2级的盒子最多能够装下4个1级的盒子；</p>
<p>......</p>
<p>一个L级的盒子最多能够装下4个K-1级的盒子；</p>
<p>问题是，给出一些盒子 ：Li级别的有Bi个，问最小能够用一个级别为多大的盒子来装下所有的盒子呢？</p>
<p> </p>
<p>上图是样例，表示给出5个级别1的盒子，3个级别2的盒子，至少要用一个级别为3的盒子来装下所有的盒子。</p>

<img src="/source/codevs/codevs-2285/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMjg1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NzQyNDk5MC4xOTAuODg2NTEwNjQ1MTU3LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，输入一个整数n(1&lt;=n&lt;=10^5) 表示有n种不同级别的盒子</p>
<p>接下来n行</p>
<p>每行输入两个整数Li(0&lt;=Li&lt;=10^9)和Bi (1&lt;=Bi&lt;=10^9)表示级别为Li的盒子 有 Bi个、</p>
<p>有多组数据 输入以EOF结束</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">最少要用一个级别为&nbsp;OP的盒子，能够装下所有盒子</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>0 3<br>1 5</p>
<p> </p>
<p>1<br>0 4</p>
<p> </p>
<p>2<br>1 10<br>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p> </p>
<p>1</p>
<p> </p>
<p>3</p>
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
<p>不会很大，因为数据量也不大</p>
</div>
</div>