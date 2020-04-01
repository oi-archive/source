<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>天使城有一个火车站，每辆火车都从A方向驶入车站，<br>再从B方向驶出车站。</p>
<p> </p>
<p>为了调度火车，火车站设有停放轨道，可存放5辆火车。已知从A进入车站顺序为1、2、3……。现在给你一个调度方案，判断是否可行，如果可行，输出出站顺序。<br>有以下几种调度方法：<br>A. 将A上的头一辆车驶出B方向<br>B. 将A上的头一辆车停入暂停轨道<br>C. 将暂停轨道上最外面的车驶出B方向</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行一个整数N(n&lt;30)表示调度方案步骤数目。<br>下一行一个字符串，有N个大写字母，表示调度方法。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出若不可行（暂停站满了还停车、暂停站空了还出车），则输出一行&ldquo;No&rdquo;。<br />若可行，输出一行&ldquo;Yes&rdquo;，再输出若干行，每行一个整数，表示车出站序列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>[样例输入1]<br>6<br>ABBCCA<br>[样例输入2]<br>5<br>BACAC</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>[样例输出1]<br>Yes<br>1<br>3<br>2<br>4<br>[样例输出2]<br>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如题</p>
</div>
</div>