<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一场战争中，战场由<span style="font-family: 'Times New Roman';">n</span><span style="">个岛屿和</span><span style="font-family: 'Times New Roman';">n-1</span><span style="">个桥梁组成，保证每两个岛屿间有且仅有一条路径可达。现在，我军已经侦查到敌军的总部在编号为</span><span style="font-family: 'Times New Roman';">1</span><span style="">的岛屿，而且他们已经没有足够多的能源维系战斗，我军胜利在望。已知在其他</span><span style="font-family: 'Times New Roman';">k</span><span style="">个岛屿上有丰富能源，为了防止敌军获取能源，我军的任务是炸毁一些桥梁，使得敌军不能到达任何能源丰富的岛屿。由于不同桥梁的材质和结构不同，所以炸毁不同的桥梁有不同的代价，我军希望在满足目标的同时使得总代价最小。</span></p>
<p>侦查部门还发现，敌军有一台神秘机器。即使我军切断所有能源之后，他们也可以用那台机器。机器产生的效果不仅仅会修复所有我军炸毁的桥梁，而且会重新随机资源分布（但可以保证的是，资源不会分布到<span style="font-family: 'Times New Roman';">1</span><span style="">号岛屿上）。不过侦查部门还发现了这台机器只能够使用</span><span style="font-family: 'Times New Roman';">m</span><span style="">次，所以我们只需要把每次任务完成即可。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数<span style="font-family: 'Times New Roman';">n</span><span style="">，代表岛屿数量。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">n-1</span><span style="">行，每行三个整数</span><span style="font-family: 'Times New Roman';">u,v,w</span><span style="">，代表</span><span style="font-family: 'Times New Roman';">u</span><span style="">号岛屿和</span><span style="font-family: 'Times New Roman';">v</span><span style="">号岛屿由一条代价为</span><span style="font-family: 'Times New Roman';">c</span><span style="">的桥梁直接相连，保证</span><span style="font-family: 'Times New Roman';">1&lt;=u,v&lt;=n</span><span style="">且</span><span style="font-family: 'Times New Roman';">1&lt;=c&lt;=100000</span><span style="">。</span></p>
<p>第<span style="font-family: 'Times New Roman';">n+1</span><span style="">行，一个整数</span><span style="font-family: 'Times New Roman';">m</span><span style="">，代表敌方机器能使用的次数。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">m</span><span style="">行，每行一个整数</span><span style="font-family: 'Times New Roman';">k</span>i，代表第<span style="font-family: 'Times New Roman';">i</span><span style="">次后，有</span><span style="font-family: 'Times New Roman';">k</span>i个岛屿资源丰富，接下来<span style="font-family: 'Times New Roman';">k</span><span style="">个整数</span><span style="font-family: 'Times New Roman';">h</span>1,h2,…hk，表示资源丰富岛屿的编号。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出有<span style="font-family: 'Times New Roman';">m</span><span style="font-family: 宋体;">行，分别代表每次任务的最小代价。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10</p>
<p>1 5 13</p>
<p>1 9 6</p>
<p>2 1 19</p>
<p>2 4 8</p>
<p>2 3 91</p>
<p>5 6 8</p>
<p>7 5 4</p>
<p>7 8 31</p>
<p>10 7 9</p>
<p>3</p>
<p>2 10 6</p>
<p>4 5 7 8 3</p>
<p>3 9 4 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>
<p>32</p>
<p>22</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于<span style="font-family: 'Times New Roman';">10%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">2&lt;=n&lt;=10,1&lt;=m&lt;=5,1&lt;=k</span>i&lt;=n-1</p>
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">2&lt;=n&lt;=100,1&lt;=m&lt;=100,1&lt;=k</span>i&lt;=min(10,n-1)</p>
<p>对于<span style="font-family: 'Times New Roman';">40%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">2&lt;=n&lt;=1000,m&gt;=1,sigma(k</span>i)&lt;=500000,1&lt;=ki&lt;=min(15,n-1)</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">2&lt;=n&lt;=250000,m&gt;=1,sigma(k</span>i)&lt;=500000,1&lt;=ki&lt;=n-1</p>
<p> </p>
</div>
</div>
</div>