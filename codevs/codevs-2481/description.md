<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>宫殿的大门打开了，里面漆黑一片，藏宝图上记载，必须要点亮灯阵，宫殿内的各种陷阱才会关闭，才能进入宫殿深处，否则每一步都有极大的危险。这个灯阵是由很多盏油灯组成，它们排成长长的一行。这些油灯经过巧妙的设计，有很多种型号，每种型号都有专用的点灯工具。假设每盏灯都有一个类型编号p（1&lt;=p&lt;=2,000,000,000）。那么点灯工具也有不同的编号s（1&lt;=s&lt;=2,000,000,000）。每盏灯只能被与自己编号相同的点灯工具点燃，例如1号类型的灯只能被编号为1的点灯工具点燃。灯阵旁边就有古代的点灯器，它是一个类似树杈的东西，后端一个粗把手，前端有一些分叉。<strong>只不过前端的分叉可以任意增加和减少，每个分叉末端都必须正好安装一种点灯工具，</strong>这样就可以同时点燃数个灯，但是<strong>点灯工具一旦安装上就无法去掉</strong>，所以分叉的个数与点灯工具的安装都要经过精细的计算。经过现场仔细的观察和对藏宝图的研究，小可可了解到灯的分布情况与点燃的方式为：</p>
<p>1、所有灯按顺序排成一行，位置从左到右分别为1,2,3,……,n，称为1号位、2号位等等，每两条相邻的灯的间隔是相等的，可以有重复型号的灯。</p>
<p>2、点灯器分叉的末端在一条直线上，上面必须挂m个点灯工具，每两个相邻的点灯工具的间隔相等，且等于每两条相邻的灯的间隔；</p>
<p>3、从最左边的灯开始，把点灯器上最左边的点灯工具与最左边的灯对齐，分叉末端点灯工具的排列方向与灯排列的方向相同，且必须保证所有点灯工具的编号与那个要点燃的灯的编号相等；然后就可以点灯了。灯一旦点燃就不会熄灭。</p>
<p>4、点灯的过程就是从最左边开始，不断向右走（<strong>从不往回走，也不掉转点灯器的方向</strong>），寻找下一个点灯的位置。必须仍然保证所有点灯工具的编号与要点燃的灯的编号相等，而且每个点灯工具下都必须有灯；</p>
<p>5、一定要保证所有的灯都被点燃（当然，可能有一些灯被点了多次）。只有这样，灯阵才算被真正点亮，也才能进行下一步探宝。</p>
<p> </p>
<p>灯阵旁边有足够多的各种型号的点灯工具。如果点灯器前端的分叉数量大于等于1且小于等于n，那么需要多少个分叉能够保证成功点亮灯阵呢？ 小可可想麻烦你来帮他计算所有可能的情况，他会根据你的计算最终确定合适的点燃灯阵的方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中第一行有一个整数n（1&lt;=n&lt;=500,000），表示灯阵中灯的数目。</p>
<p>下面有n行每行有一个数字，第i个数字表示从左数第i号位灯的类型编号p（1&lt;=p&lt;=2,000,000,000）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出所有满足要求的分叉的数目。每行输出一个数，要求从小到大输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>2</p>
<p>2</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>2</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>