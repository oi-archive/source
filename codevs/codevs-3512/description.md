<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>要做出绝顶美味让人大快朵颐的肉鸡翅，需要放入很多美味的调料。<br>此时麦当劳来了一位大客户，他要n*m个鸡翅，并且要求用一个带铁丝网格的<br>巨大n行m列铁板装着鸡翅（每个格子里装一个），每个格子里的鸡翅必须用此<br>客户指定的调料（不尽相同），然后此客户将这个铁板整个带回家当艺术品享用。<br>铁板被分成n*m 个方格，每一个格子都只能放上带指定调料的鸡翅，调料是不<br>能覆盖的，即假如P格要放x味的调料，那么不能先放上y味的调料再放上x味<br>的调料。<br>麦当劳首席大厨TYG很崇尚艺术，他买了一台自动洒调料机，有三种洒调料方法：<br>A. 将同一行某些连续的格子洒上同一种味道的调料，机器损耗的代价为a <br>B. 将同一列某些连续的格子洒上同一种味道的调料，机器损耗的代价为b <br>C. 将某一个格子撒上某种味的调料，机器损耗的代价为c <br>现在TYG想要一种代价最少的方案将这些鸡翅按客户指定的要求撒上调料。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>本题有多组数据（有很多那种大客户来订单，引进肉鸡品牌后销量明显增了很多），<br>首先第一行输入数据组数，<br>每组数据的输入如下：<br>第一行五个整数n,m,a,b,c <br>接下来一个n*m 的矩阵，表示每一个网格中应洒调料的种类，调料种类用小写<br>字母表示。<br>（注：不保证字母是连续的出现的。也就是说可能只出现了a和c两种字母）<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组数据，输出一个整数ans，表示最小代价<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 <br>3 4 11 8 3 <br>aaaa <br>aaaa <br>aaaa <br>4 4 3 5 2 <br>aabc <br>aabc <br>bbbb <br>ccbc <br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>32 <br>23 <br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据组数不超过  40。<br>1&lt;=n,m&lt;=30 <br>1&lt;=a,b,c&lt;=100000<br></p>
</div>
</div>