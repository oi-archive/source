<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>管道取珠是小X很喜欢的一款游戏。在本题中，我们将考虑该游戏的一个简单改版。游戏画面如图1所示。</p>
<p>游戏初始时，左侧上下两个管道分别有一定数量的小球（有深色球和浅色球两种类型），而右侧输出管道为空。每一次操作，可以从左侧选择一个管道，并将该管道中最右侧的球推入右边输出管道。</p>
<p>例如：我们首先从下管道中移一个球到输出管道中，将得到图2所示的情况。</p>
<p>假设上管道中有n个球, 下管道中有m个球，则整个游戏过程需要进行n+m次操作，即将所有左侧管道中的球移入输出管道。最终n+m个球在输出管道中从右到左形成输出序列。</p>
<p>爱好数学的小X知道，他共有C(n+m，n)种不同的操作方式，而不同的操作方式可能导致相同的输出序列。举个例子，对于图3所示的游戏情形。</p>
<p>我们用A表示浅色球，B表示深色球。并设移动上管道右侧球的操作为U，移动下管道右侧球的操作为D，则共有C(2+1，1)=3种不同的操作方式，分别为UUD，UDU，DUU；最终在输出管道中形成的输出序列（从右到左）分别为BAB，BBA，BBA。可以发现后两种操作方式将得到同样的输出序列。</p>
<p>假设最终可能产生的不同种类的输出序列共有K种，其中：第i种输出序列的产生方式（即不同的操作方式数目）有a<sub>i</sub>个。聪明的小X早已知道，</p>
<p> </p>
<p>因此，小X希望计算得到：</p>
<p> </p>
<p>你能帮助他计算这个值么？由于这个值可能很大，因此只需要输出该值对1024523的取模即可（即除以1024523的余数）。</p>
<p>说明：文中C(n+m，n)表示组合数。组合数C(a，b)等价于在a个不同的物品中选取b个的选取方案数。</p>
<p> </p>

<img src="/source/codevs/codevs-1847/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xODQ3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTg0Ny5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中的第一行为两个整数n，m，分别表示上下两个管道中球的数目。</p>
<p>第二行中为一个AB字符串，长度为n，表示上管道中从左到右球的类型。其中：A表示浅色球，B表示深色球。</p>
<p>第三行中为一个AB字符串，长度为m，表示下管道中的情形。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中仅一行为一个整数，即为&nbsp;&nbsp; 除以1024523的余数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 1</p>
<p>AB</p>
<p>B</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>样例即为文中（图3）。共有两种不同的输出序列形式，序列BAB有1种产生方式，而序列BBA有2种产生方式，因此答案为5。</p>
<p> </p>
<p>【数据规模和约定】</p>
<p>对于30%的数据，满足：m，n&lt;=12；</p>
<p>对于100%的数据，满足：m，n&lt;=500。</p>
</div>
</div>