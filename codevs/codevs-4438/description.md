<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>学校科技楼一共有N层,而神犇YJQ每天都在科技楼N楼的机房写代码。这天,他准备从科技楼1楼爬到N楼。有个M连接不同楼层的楼梯,爬每个楼梯需要一定的体力值。楼梯一定是从低处通往高处的。(但是由于楼房的设计比较奇怪,第i楼并不一定在第i-1楼上面,也就是说给出的边不保证x&lt;y,但保证图为DAG,请自行处理楼层之间的高度关系)。为了省时间,YJQ一定只会上楼梯而不会下楼梯,即楼梯间不会形成环路。而且出于人性化考虑,不管YJQ选择什么路线上楼,他爬的楼梯数量一定小于20。为了使体力消耗尽量平稳,YJQ需要选择一条“每个楼梯消耗体力值的方差最小”的路径上楼。请帮助YJQ计算出这个最小方差。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含2个整数N,M表示科技楼楼层数和楼梯数; 接下来M行,每行3个数,x,y,z表示存在一条由x层通往平台y层的楼梯,爬这个楼梯需要消耗z的体力值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行1个实数,表示最小方差,精确到小数点后4位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 4 1 2 1 2 4 3 1 3 2 3 4 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">0.2500</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据,N&lt;=10,M&lt;=20; </p><p>另有20%的数据N&lt;=35,M&lt;=220,Z∈0,1; </p><p>对于100%的数据2&lt;=N&lt;=50,M&lt;=300,0&lt;=Z&lt;=50保证至少存在一条由1到N的路径。</p>
</div>
</div>