<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>（经典问题系列第一题）</p><p><em>vhenry</em> 拥有一个巨型的谷仓，可是他忘了，在谷仓的一角有一个小洞。</p><p>第一天时谷仓是满的，第 <em>i</em> 天 <em>vhenry</em> 会派 <em>zhr</em> 在谷仓中放入 <em>m</em> 颗谷物，但是会有麻雀叼走 <em>i</em> 颗谷物，而且谷仓的容量上限为 <em>n</em> 颗谷物 （也就是说，如果满了就无法放入）。</p><p>有一天 <em>vhenry</em> 去视察谷仓，可是谷仓已经空空如也，他很生气，于是请你帮他算一算第几天谷仓第一次为空。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包括两个数 <em>n</em> 和 <em>m</em>，<em>n</em> 表示谷仓的最大容量，<em>m</em> 表示每天放入的谷物数目。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅包含一个整数，表示第几天谷仓第一次为空。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">5 2</p>

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
<p>数据范围：</p><p><strong>对于 100% 的数据，1 <span style="font-family: Merriweather, serif;">≤</span> <em>n</em>, <em>m</em> <span style="font-family: Merriweather, serif;">≤</span> <span style="text-decoration: underline;">10^18</span>。（本题数据很恶心）</strong></p><p><strong>-------------------------------------------------------------</strong></p><p>样例解读：</p><p>第一天放入后谷仓有 5 颗谷物，叼走后还剩下 4 颗谷物。<br></p><p>第二天放入后谷仓有 5 颗谷物，叼走后还剩下 3 颗谷物。</p><p>第三天放入后谷仓有 5 颗谷物，叼走后还剩下 2 颗谷物。</p><p>第四天放入后谷仓有 4 颗谷物，叼走后还剩下 0 颗谷物。</p><p>所以第四天谷仓第一次为空。</p><p><strong style="">-------------------------------------------------------------</strong></p><p><span style="text-decoration: none;">提示：</span></p><p><span style="text-decoration: none;">题目标签：【二分答案】。</span></p><p><span style="text-decoration: none;">思路提示 （<em>Hint</em>）和代码可以看题解的最后四个。</span><span style="text-decoration: none;"></span></p>
</div>
</div>