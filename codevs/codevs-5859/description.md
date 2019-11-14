<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>很久很久以前，在ly森林里住着一个ly和一个WYL，森林里的ly树十分茂密，ly和WYL十分快乐。但是有一天，小明开着挖土机进入了ly森林，把大部分的ly树给铲倒了。WYL醒来时看到了如此的场景就哭着跑走了，只留下ly孤单地生活在ly森林里。ly想在所有的树坑上中上新的WYL树，而且ly新种下去的WYL树有一个奇特的生长规律，就是每棵WYL树，两年就会分裂一次，每次分裂都会往自己的坐标的上下左右都生长出一颗新的WYL树，新的WYL树也会按照此规律分裂。</p><p>ly森林里的树木用二维函数表示，‘0’代表被小明挖掉的树桩，而‘1’代表完整的树。</p><p>被小明挖完了之后的森林（示例）</p><p>0 0 0 0 0</p><p>1 1 0 0 0</p><p>1 0 0 0 0</p><p>0 1 0 0 1</p><p>现在告诉你森林的横纵坐标m,n,以及WYL树能够生长的时间x,还有森林里的树的状态，求出ly最少只需种几棵WYL树（因为每棵WYL树苗都很贵，要三百个白熊币）就能长出一个完整的新的森林？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：m n x</p><p>第二行到第n+1行输入森林的状态</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数字，代表ly至少要种几棵树。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4 2</p><p>1 0 1 0 1</p><p>0 0 1 0 0</p><p>0 1 1 1 1</p><p>0 0 0 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>m,n小于40 大于等于2</p>
</div>
</div>