<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>晴朗的夜晚，小W最喜欢仰望星空。</p><p>小W发现，每一颗星星都有3种数值：亮度、光度和大小</p><p>为了更好地观察星空，小W给每颗星星定义了一个“耀眼值”。一个星星的“耀眼值”，就是指亮度、光度和大小都<strong><span style="">不大于</span></strong>该星的星星个数。</p><p>现在，小W想知道，最耀眼的星星的“耀眼值”是多少。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""></span></p><p>
第一行两个数字N，M，代表有N颗星星。</p><p>
第二行三个数字X，Y，Z，代表第一颗星的亮度、光度和大小。</p><p>第三行三个数字A，B，C，若第i颗星的亮度为Xi，光度为Yi，大小为Zi，那么第i+1颗星星的亮度为(A*Xi^2+B*Xi+C) mod M，光度为(A*Yi^2+B*Yi+C) mod M，大小为(A*Zi^2+B*Zi+C) mod M</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，代表最大的“耀眼值”。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 10007</p><p>3 0 0</p><p>1 1 1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，N&lt;=50000，M,X,Y,Z&lt;=100000000，A,B,C&lt;=10<br></p>
</div>
</div>