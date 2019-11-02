<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    张蒙，蒋帅，周杰相信自己想要的幸福在不远的未来。然而，张蒙，蒋帅，周杰想要得到这幸福，还需要走很长一段路。张蒙认为他、蒋帅、周杰的幸福可以想象成n*m的格子状机房。左上角的格子为(1,1)，右下角的格子为n，m；蒋帅和周杰有许多得意的学生（如<em>wmg</em>，<em>dyc</em>，zyc，zzj，yyy等等）这些学生看上n*m个妹子，于是蒋帅和周杰将妹子放在机房让张蒙先帮神犇们进行挑选(妹子的权值Aij都两两不同）。不幸的是，蒋帅和周杰觉得这些妹子中有的质量实在太让人绝望（在这里不做点名大家都懂），她们的权值Aij=0。更进一步说，对于Aij&gt;0的妹子，权值两两不同。（p.s.对于学oi的妹子蒋帅认为不能再赞所以不允许张蒙进行挑选，她希望这些妹子自己找到幸福。所以挑选时应找权值较小但不为零的。）（pps.对于某不愿透露姓名的自己作死放弃幸福挑选的fjk，周杰表示自己幸福的梦想难以实现所以很受伤。。。）</p><p>    张蒙站在机房的起点(1,1)，他想要走向人生的巅峰（即蒋帅所在的机房右下角）(n,m)。蒋帅认为人只能前进，即若张蒙站在(a,b)，他只能走向(a,b+1)或者(a+1,b)（后退会被蒋帅打掉牙）。并且张蒙认为不好的妹子是绝对不可以让学生触碰的，因为一旦撩到就会坠入万丈深渊。张蒙会将自己所挑选成功的妹子的权值依次写出，形成一个n+m-1的序列。张蒙想知道其中字典序最小的序列（保证前面的数字尽量小）是什么。若是妹子过于让人失望，没有一个合法序列，就输出"Oh,the girls are too disappointing!”，不包含引号。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入的第一行是两个正整数<span style="font-family: Times New Roman;">n</span><span style="">和</span><span style="font-family: Times New Roman;">m</span><span style="">。</span></span></p><p><span style=""><span style="">接着是</span><span style="font-family: Times New Roman;">n</span><span style="">行</span><span style="font-family: Times New Roman;">m</span><span style="">列的妹子机房。</span></span></p><p><span style=""><span style=""><br></span></span></p><p><span style=""><span style=""><br></span></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体;font-size:16px">输出只有一行，如果存在合法序列，则为<span style="font-family:Times New Roman">n+m-1</span><span style="font-family:宋体">个用一个空格隔开的权值。</span></span></p><p><span style=";font-family:宋体;font-size:16px"><span style="font-family:宋体">否则就输出</span></span>Oh,the girls are too disappointing!</p><p><span style=";font-family:宋体;font-size:16px"><span style="font-family:Times New Roman"></span></span><br/></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 3</span></p><p><span style="">1 3 4</span></p><p><span style="">11</span><span style=""> 9 0</span></p><p><span style="">5 6 8</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">1 3 9 6 8</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于<span style="font-family: Times New Roman;">20%</span><span style="">的数据 </span><span style="font-family: Times New Roman;">n&lt;10 m&lt;10</span></span></p><p><span style="">对于<span style="font-family: Times New Roman;">60%</span><span style="">的数据 </span><span style="font-family: Times New Roman;">n&lt;=300 m&lt;=300</span></span></p><p><span style="">对于<span style="font-family: Times New Roman;">100%</span><span style="">的数据 </span><span style="font-family: Times New Roman;">n&lt;=1000 m&lt;=1000 Aij&lt;=1e9</span></span></p><p><br></p>
</div>
</div>