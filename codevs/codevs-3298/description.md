<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>GFS<span style="">准备了一场丰厚的晚宴来宴请他的</span><span style="font-family: 'Times New Roman';">MM</span><span style="">们，共有</span>n个<span style="font-family: 'Times New Roman';">MM</span><span style="">要来参加这场宴会，</span><span style="font-family: 'Times New Roman';">GFS</span><span style="">为她们准备了</span>m种菜品。但并不是每个 <span style="font-family: 'Times New Roman';">MM</span><span style="">都喜欢所有的菜，每个</span><span style="font-family: 'Times New Roman';">MM</span><span style="">都有自己喜欢吃菜品，而如果餐桌上相邻两个</span><span style="font-family: 'Times New Roman';">MM</span><span style="">有共同喜欢的菜，她们就会互相争抢。为了维护世界的和谐，聪明的 </span><span style="font-family: 'Times New Roman';">GFS</span><span style="">必须合理安排好他的</span><span style="font-family: 'Times New Roman';">MM</span><span style="">们的座次。每张餐桌都是圆形的，</span><span style="font-family: 'Times New Roman';">GFS</span><span style="">拥有足够多的桌子来安排他的 </span><span style="font-family: 'Times New Roman';">MM</span><span style="">，但是为了防止</span><span style="font-family: 'Times New Roman';">MM</span><span style="">们产生孤单的感觉，不允许有</span><span style="font-family: 'Times New Roman';">MM</span><span style="">单桌的情形，也就是说每张桌子至少有两个</span><span style="font-family: 'Times New Roman';">MM</span><span style="">。当然了，每个</span><span style="font-family: 'Times New Roman';">MM</span><span style="">都不能与旁边的两个</span><span style="font-family: 'Times New Roman';">MM</span><span style="">有共同喜欢吃的菜。</span></p>
<p>问是否存在这样的安排方案使得每个<span style="font-family: 'Times New Roman';">MM</span><span style="">都能满意。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数T，表示数据组数。</p>
<p>对于每个测试数据，第一行为两个正整数n和m。</p>
<p>接下来n行，每行第一个数k，表示这个<span style="font-family: 'Times New Roman';">MM</span><span style="">有</span>k个喜欢的菜品，之后k个数为<span style="font-family: 'Times New Roman';">MM</span><span style="">喜欢的菜品的编号。菜品编号为</span><span style="font-family: 'Times New Roman';">1</span><span style="">到</span>m。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p18">共包含T行，每行&ldquo;<span style="font-family: 'Times New Roman';">Yes</span><span style="font-family: 宋体;">&rdquo;或&ldquo;</span><span style="font-family: 'Times New Roman';">No</span><span style="font-family: 宋体;">&rdquo;。&ldquo;</span><span style="font-family: 'Times New Roman';">Yes</span><span style="font-family: 宋体;">&rdquo;表示存在一种方案，&ldquo;</span><span style="font-family: 'Times New Roman';">No</span><span style="font-family: 宋体;">&rdquo;表示不存在。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>3 4</p>
<p>2 2 4</p>
<p>1 3</p>
<p>1 2</p>
<p>5 4</p>
<p>2 1 3</p>
<p>2 2 4</p>
<p>1 2</p>
<p>1 3</p>
<p>1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>No</p>
<p>Yes</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据：</span>N ≤ 16<span style="">。</span></p>
<p>另有<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据：</span>M ≤ 2<span style="">。</span></p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据：</span><span style="font-family: 'Times New Roman';">1 </span>≤ T ≤ 10<span style="">，</span><span style="font-family: 'Times New Roman';">1 </span>≤ N ≤ 500<span style="">，</span><span style="font-family: 'Times New Roman';">1 </span>≤ M ≤ 30<span style="">。</span></p>
</div>
</div>