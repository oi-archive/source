<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">你突然有了一个大房子，房子里面有一些房间。事实上，你的房子可以看做是一个包含</span>n*m<span style="">个格子的格状矩形，每个格子是一个房间或者是一个柱子。在一开始的时候，相邻的格子之间都有墙隔着。</span></p><p style=""><span style="">你想要打通一些相邻房间的墙，使得所有房间能够互相到达。在此过程中，你不能把房子给打穿，或者打通柱子（以及柱子旁边的墙）。同时，你不希望在房子中有小偷的时候会很难抓，所以你希望任意两个房间之间都只有一条通路。现在，你希望统计一共有多少种可行的方案。</span></p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行两个数分别表示</span>n<span style="">和</span>m<span style="">。</span></p><p style=""><span style="">接下来</span>n<span style="">行，每行</span>m<span style="">个字符，每个字符都会是</span>’.’<span style="">或者</span>’*’<span style="">，其中</span>’.’<span style="">代表房间，</span>’*’<span style="">代表柱子。</span></p><p> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">一行一个整数，表示合法的方案数。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【样例输入</span>1</strong><strong><span style="">】</span></strong></p><p>2</p><p>..</p><p>..</p><p> </p><p><strong><span style="">【样例输出</span>1</strong><strong><span style="">】</span></strong></p><p>4</p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【样例输入</span>2</strong><strong><span style="">】</span></strong></p><p>2</p><p>*.</p><p>.*</p><p> </p><p><strong><span style="">【样例输出</span>2</strong><strong><span style="">】</span></strong></p><p>0</p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于前</span>20%<span style="">的数据，</span>n,m &lt;= 3</p><p><span style="">对于前</span>50%<span style="">的数据，</span>n,m &lt;=5</p><p><span style="">对于前</span>100%<span style="">的数据，</span>n,m&lt;=9</p><p><span style="">有</span>40%<span style="">的数据保证，</span>min(n,m)&lt;=3</p><p><span style="">有</span>30%<span style="">的数据保证，不存在柱子</span></p><p> </p><p><br></p>
</div>
</div>