<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>USACO 2010 Jan</p><p><br></p><p>约翰在镇上，沿着公路开车回家，他的家离起点有 E公里。他顺便准备买K吨饲料。</p><p>运送饲料是要花油钱的，如果他车上有 X 吨饲料，行驶一公里需要 X元，行驶 D公里就需要 DX元。约翰可以从 N家商店购买饲料，所有商店都在公路边上，第i家店距离起点 Xi公里，饲料单价为每吨 Ci元，库存为 Fi吨。</p><p><br></p><p>约翰可以选择在任意商店里购买任意多的饲料，只要那家还有货就可以了。</p><p>保证所有商店的饲料库存之和不会少于 K，为了带 K吨饲料回家，约翰最少的花费是多少呢？</p><p><br></p><p>举个例子，假设有三家商店情况如下所示：</p><p>坐标 X=1 X=3 X=4 E=5</p><p>库存  1   1   1</p><p>单价  1   2   2</p><p>如果约翰要买 2吨饲料回家，那么他的最好选择是在离家较近的两商店购买饲料，则花在路上的钱是 1+2=3，花在商店的钱是 2+2=4，共需要 7元。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：三个用空格分开的整数</p><p>第二行到第N+1行：三个用空格分开的整数：Xi，Fi和Ci</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行,单个整数，购买和运送饲料的最小总费用</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 5 3</p><p>3 1 2</p><p>4 1 2</p><p>1 1 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">1 ≤ K，N ≤ 100， 1 ≤ E ≤ 350</p><p style="">0 &lt; Xi &lt; E，1 ≤ Fi ≤ 100，1 ≤ Ci ≤10^6</p><p><br></p>
</div>
</div>