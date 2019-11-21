<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>YHZ大神在做KZ的一次测验时，一直都是WA，他特别生气，就去看了看数据。结果...数据错了！可是KZ已经离开了机房，YHZ只有自己造数据了。KZ的电脑将在下课时自动关闭，YHZ手打数据需要很长时间，越复杂的数据花的时间越多。<strong>一个数据有固定的t值（YHZ需要打的时间）和价值。</strong>YHZ希望在下课前打完尽可能多的数据，<strong>但如果一个数据没打完就下课了，这个数据就是没有用的。假设数据0ms在打完后就可以发出去</strong>，YHZ想知道自己最多可以打多少组数据，并让价值尽可能大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数n和t，表示有多少组数据和距离下课的时间</p><p>第二行一个数stu，表示学生数量，且每个学生期望的价值从1开始递增</p><p>接下来n行，两个数，v和u，表示打的时间和这个数据的价值</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行两个数ans和c，表示最多能打的数据的个数和能满足的学生数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5</p><p>7</p><p>2 1</p><p>3 4</p><p>1 2</p><p>4 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6<br></p><p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例数据<strong>部分</strong>解释:</p><p><strong>学生期望的价值为:1 2 3 4 5 6 7</strong></p><p><span style=""><strong>保证学生期望价值两两的差均为1</strong></span></p><p><span style=""></span></p><hr><p>数据范围<span style=""></span><br></p><p>30%数据保证1&lt;=n&lt;=200,1&lt;=t&lt;=200,1&lt;=stu&lt;=234<br></p><p>100%数据保证1&lt;=n&lt;=1000,1&lt;=t&lt;=1000,1&lt;=stu&lt;=2000,1&lt;=v&lt;=10000,0&lt;=u&lt;=10000</p><hr><p>提示</p><p><strong>dp</strong></p>
</div>
</div>