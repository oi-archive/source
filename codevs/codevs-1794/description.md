<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>ZZ对数学饱有兴趣，并且是个勤奋好学的学生，总是在课后留在教室向老师请教一些问题。</p>
<p>一天他早晨骑车去上课，路上见到一个老伯正在修剪花花草草，顿时想到了一个有关修剪花卉的问题。</p>
<p>于是当日课后，ZZ就向老师提出了这个问题：</p>
<p>一株奇怪的花卉，上面共连有N 朵花，共有N-1条枝干将花儿连在一起，并且未修剪时每</p>
<p>朵花都不是孤立的。</p>
<p>每朵花都有一个“美丽指数”，该数越大说明这朵花越漂亮，也有“美丽指数”为负数的，</p>
<p>说明这朵花看着都让人恶心。</p>
<p>所谓“修剪”，意为：去掉其中的一条枝条，这样一株花就成了两株，扔掉其中一株。</p>
<p>经过一系列“修剪“之后，还剩下最后一株花（也可能是一朵）。</p>
<p>老师的任务就是：通过一系列“修剪”（也可以什么“修剪”都不进行），使剩下的那株（那</p>
<p>朵）花卉上所有花朵的“美丽指数”之和最大。</p>
<p>老师想了一会儿，给出了正解（交大的老师是很牛的~）。ZZ见问题被轻易攻破，相当不爽，</p>
<p>于是又拿来问你。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数N(1 ≤ N ≤ 16000)。表示原始的那株花卉上共N 朵花。</p>
<p>第二行有N 个整数，第I个整数表示第I朵花的美丽指数。</p>
<p>接下来N-1行每行两个整数a,b，表示存在一条连接第a 朵花和第b朵花的枝条。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">一个数，表示一系列&ldquo;修剪&rdquo;之后所能得到的&ldquo;美丽指数&rdquo;之和的最大值。保证绝对值不超</p>
<p align="left">过2147483647。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>-1 -1 -1 1 1 1 0</p>
<p>1 4</p>
<p>2 5</p>
<p>3 6</p>
<p>4 7</p>
<p>5 7</p>
<p>6 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>数据范围：</strong></p>
<p>对于 60%的数据， 保证N≤1,000</p>
<p>对于100%的数据，保证N≤16,000</p>
</div>
</div>