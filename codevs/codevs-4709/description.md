<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">多肽是α-氨基酸以肽链连接在一起而形成的化合物，它也是蛋白质水解的中间产物。由两个氨基酸分子脱水缩合而成的化合物叫做二肽，同理类推还有三肽、四肽、五肽等。通常由三个或三个以上氨基酸分子脱水缩合而成的化合物都可以叫多肽。</p><p style="">为了计算病毒结构与蛋白质性质，现取出M种氨基酸混合，已知其相对分子质量为C1，C2，C3……经过精密的脱水缩合反应形成了大量多种多样的肽链。需要预测有多少种肽链水解后相对分子质量为n。（A-B-C和C-B-A两条肽链视为不同）</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行两个整数n,m;</p><p style="">第二行m个整数，第i个数ci表示第i种氨基酸的相对分子质量。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(88, 102, 110); font-family: &#39;Source Sans Pro&#39;, &#39;Helvetica Neue&#39;, Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);">一个整数表示方案数除以1005060097的余数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2</p><p>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">对于30%的数据，n,m,c&lt;=5000</p><p style="">对于100%的数据，n,m,c&lt;=100000</p><p style="">对于样例的解释：</p><p style="">1-1-1-1</p><p style="">1-1-2</p><p style="">1-2-1</p><p style="">2-1-1</p><p style="">2-2</p><p style="">共5种。</p><p style="">题目来自Nescafe41 Problem A 异化多肽。</p><p style="">由于测试数据大小限制题目只保留了6个数据。</p>
</div>
</div>