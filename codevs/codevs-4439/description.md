<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>神犇YJQ有n个不同的妹子和m种食物,每一天每一种食物只供应一个妹子吃的份量。在接下来的t天内,YJQ准备包养所有的妹子。 对于每个妹子,她在t天内都只会吃某些特定的食物,并且总共有q种特殊要求,每种要求是在Ti天Ai号妹子会由于特殊原因不能吃第Fi种食物。 有些时候,为了满足妹子的要求,必须改变所有妹子的喂食方案。在每一天重新分配食物会有不同的代价,YJQ不愿意付那么多钱,所以他希望改变妹子喂食方案的代价尽量少。 现在,YJQ拜托你给他的妹子制定食物分配计划,他希望在保证每个妹子每天都有食物吃的前提下,使得改变分配方案付出的代价尽量少。请求出这个最少代价。 如果YJQ无论怎么分配都无法在天内包养所有妹子(包养所有妹子即是使所有妹子在∀i(1&lt;=i&lt;=t)天都有食物),请输出“-1”。</p><p>注:第一天初始分配食物并不需要花费</p><p style=""><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行4个整数n,m,t,q表示YJQ的妹子个数,食物种类数,天数,和特殊要求数; 接下来一行有t<span style="">个整数表示每一天修改食物方案的代价; 接下来n行,每行m个数,第i行第j列表示第i个妹子是否可以吃第j种食物(1表示可以,0表示不行); </span>接下来q行,每行3个整数Ti,Ai,Fi表示第Ti天Ai号妹子不能吃食物Fi</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数表示YJQ的最小花费,如果无论如何都不能包养所有妹子,输出-1</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 3 3 2 2 3 3 1 1 0 0 1 1 1 0 1 1 1 1 2 2 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">对于30%的数据,n,m,t,q&lt;4 ;</p><p style="">对于50%的数据,t&lt;20 ;</p><p style="">对于100%的数据,n,m&lt;100,t&lt;500,q&lt;10^4,所有给出的数据都是非负整数(友情提示,YJQ可能没有妹子)</p><p><br></p>
</div>
</div>