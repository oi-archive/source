<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>鉴于第一次传的题目有一个很大的bug，质子撞击炮加强版出炉啦。盟军科学家发现了质子撞击炮有一个能量传递特性，质子的能量会让围墙产生连锁反应，连环爆炸，就会对上下左右四个方向（没有斜方向）产生一点溅射伤害，如果围墙四个方向内连在一起，就会一起炸，四个方向均造成1点溅射伤害。此题目对质子炮弹做了一些改进，将会读入一个5*5的伤害矩阵，中心即为落点中心。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行 n</p>
<p>第2到第n+1行 一个n*n的敌方地形图</p>
<p>接下来五行 一个5*5的伤害矩阵（3,3）为中心，即落点</p>
<p>接下来五行 五发炮弹的落点中心（x，y）</p>
<p>（n*n的敌方地形图中，0表示空地，-1表示围墙，1~9表示建筑血量。）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两个数 第一个为摧毁的建筑数，第二个为摧毁的围墙数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>0 0 1 4 1</p>
<p>-1 -1 -1 -1 -1</p>
<p>-1 2 1 0 4</p>
<p>1 9 4 2 1</p>
<p>0 0 0 0 0</p>
<p>0 0 0 0 0 </p>
<p>0 1 1 1 0</p>
<p>0 1 2 1 0</p>
<p>0 1 1 1 0</p>
<p>0 0 0 0 0 </p>
<p>2 3</p>
<p>4 4</p>
<p>5 3</p>
<p>3 4</p>
<p>5 5</p>
<p>样例模拟x表示建筑爆炸，y表示围墙爆炸</p>
<p>【第一炮】</p>
<p>0 0 x 3 x</p>
<p>y y y y y</p>
<p>y x x 0 3</p>
<p>x 8 3 2 1</p>
<p>0 0 0 0 0</p>
<p>【第二炮】</p>
<p>0 0 x 3 x</p>
<p>y y y y y</p>
<p>y x x 0 2</p>
<p>x 8 2 x x</p>
<p>0 0 0 0 0</p>
<p>【第三炮】</p>
<p>0 0 x 3 x</p>
<p>y y y y y</p>
<p>y x x 0 x</p>
<p>x 8 2 x x</p>
<p>0 0 0 0 0</p>
<p>【第四炮】</p>
<p>0 0 x 3 x</p>
<p>y y y y y</p>
<p>y x x 0 x</p>
<p>x 7 x x x</p>
<p>0 0 0 0 0</p>
<p>【第五炮】（放空）</p>
<p>0 0 x 3 x</p>
<p>y y y y y</p>
<p>y x x 0 x</p>
<p>x 7 x x x</p>
<p>0 0 0 0 0</p>
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
<p>9</p>
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>纯模拟</p>
<p>数据n&lt;=20</p>
</div>
</div>