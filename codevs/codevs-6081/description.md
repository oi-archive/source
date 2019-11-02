<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小L有n个不同颜色的求和p个一模一样的盒子,小L想知道把这些球放进这些盒子中，且没有空盒子共有多少种方案。输出结果可能会很大，所以请模(10<sup>9</sup> + 7)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行一个正整数T，代表询问数，接下来有T行，每行有两个整数n,p，意义如题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp;&nbsp;共T行，每行对应一个询问的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>3 2</p><p>7 4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>350</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>[Hint]</strong></p><p>对于第一个询问，用a,b,c来表示三种不同颜色的球，则有下面几种方案</p><p>ab / c</p><p>ac / b</p><p>bc / a</p><p><strong>[Limit]</strong></p><p>10%的数据满足0≤p≤n≤10</p><p>30%的数据满足0≤p≤n≤1000</p><p>100%的数据满足0≤n≤10<sup>7</sup>,0≤p≤min(n,10<sup>5</sup>)，1≤T≤5</p><p>ps,不能保证程序完全正确(可能取模不到位什么的)，如果觉得数据有问题，请在题解里说一下，并在此表示抱歉。</p>
</div>
</div>