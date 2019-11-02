<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现有两个煤矿，每个煤矿都雇用一组矿工。采煤工作很辛苦，所以矿工们需要良好<br>饮食。每当一辆食品车到达煤矿时，矿工们便会产出一 定数量的煤。有三种类型<br>的食品车：肉车，鱼车和面包车。矿工们喜欢变化的食谱。如果提供的食品能够不<br>断变化，他们的产煤量将会增加。每当一个新的食品车到达煤矿时，矿工们就会比<br>较这种新的食品和前两次（或者少于两次，如果前面运送食品的次数不足两 次）<br>的食品，并且：如果这几次食品车都是同一类型的食品，则矿工们产出一个单位的<br>煤。如果这几次食品车中有两种不同类型的食品，则矿工们产出两个单位的煤。<br>如果这几次食品车中有三种不同类型的食品，则矿工们产出三个单位的煤。预先已<br>知食品车的类型及其被配送的顺序。通过确定哪车食品送到哪 个煤矿可以影响产<br>煤量。食品车不能被拆分，每个食品车必须被全部 送到一个或另一个煤矿。两个<br>煤矿也并不要求接收相同数量的食品车（事实上，也允许将所有食品车都送到一个<br>煤矿）。给出食品车的类型及其被配送的顺序，要求你写一个程序，确定哪个食品<br>车应被送到煤矿 1，哪个食品车应被送到煤矿 2，以使得两个煤矿的产煤量的总和<br>最大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个整数 n ,表示食品车的数目。第二行包含一个由 n 个字符组<br>成的字符串，按照配送顺序依次表示食品车配送的食品的类型。每个字符是以下三<br>个大写字母之一：'M' (表示肉类), 'F' (表示鱼类) 或 'B' (表示面包)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示最大的总产煤量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>16<br>MMBMBBBBMMMMMBMB</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>29</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n ≤ 10000</p>
</div>
</div>