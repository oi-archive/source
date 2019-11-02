<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>   nikola现在已经成为一个游戏里的重要人物。这个游戏有一行N个方格，N个方格用数字1..N表示。nikola开始是站在1号位置，然后能够跳到其他位置，但第一跳必须跳到2号位置。随后的每一跳必须满足以下两个条件：<br></p><p>  （1）如果是向前跳，必须比前面一跳远一个方格。</p><p>  （2）如果是向后跳，必须和前面一跳一样远。</p><p>   比如，在第一跳之后（在2号位置），nikola能够跳回1号位置，或者向前跳到4号位置。</p><p>   每次他跳入一个位置，nikola必须付费。nikola的目标是从一号位置尽可能便宜地跳到N号位置。</p><p>   请告诉nikola，跳到N号位置时的最小花费。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件 nikola.in</p><p>第1行：包含一个整数N。</p><p>第2..n+1行：第i行表示第（i-1）个方格的费用Wi。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件 nikola.out</p><p>第一行 包含一个整数t，为跳到N号格时最小花费。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：             样例2：</p><p>6                   8</p><p>1                   2</p><p>2                   3</p><p>3                   4</p><p>4                   3</p><p>5                   1</p><p>6                   6</p><p>                    1</p><p>                    4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1  12</p><p>样例2  14</p><p><br></p><p>样例1解释：</p><p>    跳格路径：1-2-1-3-6  答案为12。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据  Wi=1且n&lt;=10</p><p>对于100%的数据 n&lt;=1000 0&lt;=Wi&lt;=500 </p>
</div>
</div>