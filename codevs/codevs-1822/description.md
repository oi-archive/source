<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某国为了防御敌国的导弹袭击，发展出一种导弹拦截系统。但是这种导弹拦截系统有一个缺陷：虽然它的第一发炮弹能够到达任意的高度、并且能够拦截任意速度的导弹，但是以后每一发炮弹都不能高于前一发的高度，其拦截的导弹的飞行速度也不能大于前一发。某天，雷达捕捉到敌国的导弹来袭。由于该系统还在试用阶段，所以只有一套系统，因此有可能不能拦截所有的导弹。 </p>
<p>在不能拦截所有的导弹的情况下，我们当然要选择使国家损失最小、也就是拦截导弹的数量最多的方案。但是拦截导弹数量的最多的方案有可能有多个，如果有多个最优方案，那么我们会随机选取一个作为最终的拦截导弹行动蓝图。</p>
<p>我方间谍已经获取了所有敌军导弹的高度和速度，你的任务是计算出在执行上述决策时，每枚导弹被拦截掉的概率。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个正整数n，表示敌军导弹数量；</p>
<p>下面n行按顺序给出了敌军所有导弹信息：</p>
<p>第i+1行包含个2正整数hi和vi，分别表示第i枚导弹的高度和速度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p16">输出包含两行。</p>
<p class="p16">第一行为一个正整数，表示最多能拦截掉的导弹数量；</p>
<p class="p16">第二行包含个<span style="font-family: 'Times New Roman';">0</span><span style="font-family: 宋体;">到</span><span style="font-family: 'Times New Roman';">1</span><span style="font-family: 宋体;">之间的实数，第</span>个数字表示第i枚导弹被拦截掉的概率（5位小数）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>3 30</p>
<p>4 40</p>
<p>6 60</p>
<p>3 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>0.33333 0.33333 0.33333 1.00000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，1≤n≤1000</span>；</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，1≤n≤5*10^4</span>，1≤hi,vi≤10^9 ；</p>
<p>均匀分布着约<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，所有vi</span>均相等。</p>
<p>均匀分布着约<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，满足1≤hi,vi≤1000</span>。</p>
</div>
</div>