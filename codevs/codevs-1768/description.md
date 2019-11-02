<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了绿化乡村，H村积极响应号召，开始种树了。</p>
<p>H村里有<em>n</em>幢房屋，这些屋子的排列顺序很有特点，在一条直线上。于是方便起见，我们给它们标上1~<em>n</em>。树就种在房子前面的空地上。</p>
<p>同时，村民们向村长提出了<em>m</em>个意见，每个意见都是按如下格式：<strong>希望第</strong><strong><em>l<sub>i</sub></em></strong><strong>个房子到第</strong><strong><em>r<sub>i</sub></em></strong><strong>个房子的房前至少有</strong><strong><em>c<sub>i</sub></em></strong><strong>棵树。</strong></p>
<p>因为每个房屋前的空地面积有限，所以<strong>每个房屋前最多只能种</strong><strong><em>k<sub>i</sub></em></strong><strong>棵树</strong>。</p>
<p>村长希望<strong>在满足村民全部要求的同时，种最少的树</strong>以节约资金。请你帮助村长。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第1行，包含两个整数<em>n</em>，<em>m</em>。</p>
<p>第2行，有<em>n</em>个整数<em>k<sub>i</sub></em>。</p>
<p> 第3~<em>m</em>+1行，每行三个整数<em>l<sub>i</sub></em>，<em>r<sub>i</sub></em>，<em>c<sub>i</sub></em>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出1个整数表示在满足村民全部要求的情况下最少要种的树。<strong>村民提的要求是可以全部满足的</strong>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3</p>
<p>3 2 4 1</p>
<p>1 2 4</p>
<p>2 3 5</p>
<p>2 4 6</p>
<p> </p>
<p> </p>
<p> </p>
<p> </p>
<p> </p>
<p> </p>
<p> </p>
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
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">对于30%的数据，0&lt;<em>n</em>≤100，0&lt;<em>m</em>≤100，<em>k<sub>i</sub></em>=1；</p>
<p>对于50%的数据，0&lt;<em>n</em>≤2,000，0&lt;<em>m</em>≤5,000，0&lt;<em>k<sub>i</sub></em>≤100；</p>
<p>对于70%的数据，0&lt;<em>n</em>≤50,000，0&lt;<em>m</em>≤100,000，0&lt;<em>k<sub>i</sub></em>≤1,000；</p>
<p>对于100%的数据，0&lt;<em>n</em>≤500,000，0&lt;<em>m</em>≤500,000，0&lt;<em>k<sub>i</sub></em>≤5,000。</p>
</div>
</div>