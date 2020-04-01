<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<blockquote>
<p>【抱歉数据错误~~已修复】</p>
<p>欧盟简直是太贪心了。继完成与苏联的合作灭了尤里之后，继续与苏联交战。可惜的是，在这期间，传说中的小日本（旭日帝国·升阳帝国）居然强大起来了。盟军重新与苏联合作，准备歼灭日本。在小爱（爱因斯坦）之后，不少盟军的杰出科学家合作发明了闪电风暴二代：质子撞击炮。它的好处就是冷却时间短，威力大。每当一次攻击过后，五发质子能量炮弹一齐落在敌人基地里，造成毁灭性的打击。缺点就是，炮弹先打到外太空再掉进敌人家中，飞的时间太长了。盟军老大迫不及待的想知道这次攻击能毁掉日本多少建筑物，请你编程帮忙算一下。数据详见输入描述。</p>
</blockquote>
<div>
<h2> </h2>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<blockquote>
<p>输入的第一行n，表示敌方阵营的大小。</p>
<p>输入的第2~n+1，表示输入一个敌方阵营图。阵营图中每个元素由0-9组成。0表示没有建筑物，其余数字表示当前建筑物的血量值。（默认每个建筑物占一个方格）。</p>
<p>输入的接下来五行，表示五发质子能量炮弹的落点中心，表示落点在笛卡尔坐标系的某个点上。质子能量炮弹对中心造成2点伤害，对以该点为九宫格中心的其他八个方格造成一点伤害。如果某个点的建筑物血量被轰击至0或更低，则称这个建筑物被击毁。</p>
</blockquote>
<div>
<h2> </h2>
</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<blockquote>
<p class="p0">仅一行，被击毁的建筑物数量。</p>
</blockquote>
<div class="page-header">
<h2>&nbsp;</h2>
</div>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<blockquote>
<p>5</p>
<p>0 3 1 2 4</p>
<p>1 3 4 1 0</p>
<p>0 0 3 4 1</p>
<p>1 3 4 5 0</p>
<p>0 0 9 0 0</p>
<p>1 2</p>
<p>2 2</p>
<p>4 3</p>
<p>4 3</p>
<p>2 4</p>
</blockquote>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>(点a,点b)表示第a行第b列</p>
<p>原题有误，我更正一下。</p>
<p>顺便加强了数据（最大1000*1000的邻接矩阵）；</p>
</div>
</div>