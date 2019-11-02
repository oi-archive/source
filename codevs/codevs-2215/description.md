<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>CW在机房里放了一块正三角形的大蛋糕，但是第二天他发现蛋糕被老鼠咬坏了。</span><br><span>    </span><img><img><img title="cc"><br><span>    CW不想让蛋糕白白的被浪费，于是他把蛋糕分割成了一个个小正三角形。黑色的小正三角形表示老鼠把那一块咬坏了。CW想要切出一块最大的没被老鼠咬坏的正三角形蛋糕，可是最大的三角形有多大呢？</span></p>

<img src="/source/codevs/codevs-2215/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMjE1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMjIxNS5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span> 第一行，一个整数N，表求LPZ把蛋糕纵向划分为N行。</span><br><span>    接下来的N行，第i行包括了(n-i)*2+1个有效字符。"-"表示这块蛋糕是好的，"#"表示这块蛋糕被咬坏了。为了保持三角形的形状，输入文件中会出现空格。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一行一个整数，表示最大的三角形包括的小三角形数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5</span><br><span>#-##----#</span><br><span> -----#-</span><br><span>  ---#-</span><br><span>   -#-</span><br><span>    -</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>9</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>对于30%的数据，满足n&lt;=5</span><br><span>    对于所有的测试数据，满足n&lt;=100。</span></p>
</div>
</div>