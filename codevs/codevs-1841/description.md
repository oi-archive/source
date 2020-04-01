<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>把总质量为<span style="font-family: 'Times New Roman';">1kg</span><span style="">的水分装在</span><span style="font-family: 'Times New Roman';">n</span><span style="">个杯子里，每杯水的质量均为</span><span style="font-family: 'Times New Roman';">(1/n)kg</span><span style="">，初始温度均为</span><span style="font-family: 'Times New Roman';">0</span><span style="">℃。现需要把每一杯水都烧开。我们可以对任意一杯水进行加热。把一杯水的温度升高</span><span style="font-family: 'Times New Roman';">t</span><span style="">℃所需的能量为</span><span style="font-family: 'Times New Roman';">(4200*t/n)J</span><span style="">，其中，“</span><span style="font-family: 'Times New Roman';">J</span><span style="">”是能量单位“焦耳”。如果一旦某杯水的温度达到</span><span style="font-family: 'Times New Roman';">100</span><span style="">℃，那么这杯水的温度就不能再继续升高，此时我们认为这杯水已经被烧开。显然地，如果直接把水一杯一杯地烧开，所需的总能量为</span><span style="font-family: 'Times New Roman';">(4200*100)J</span><span style="">。</span></p>
<p>在烧水的过程中，我们随时可以在两杯温度不同的水之间进行热传递操作。热量只能从温度较高的那杯水传递到温度较低的那杯水。由于两杯水的质量相同，所以进行热传递操作之后，原来温度较高的那杯水所降低的温度总是等于原来温度较低的那杯水所升高的温度。</p>
<p>一旦两杯水的温度相同，热传递立刻停止。</p>
<p>为了把问题简化，我们假设：</p>
<p>1、 没有进行加热或热传递操作时，水的温度不会变化。</p>
<p>2、 加热时所花费的能量全部被水吸收，杯子不吸收能量。</p>
<p>3、 热传递总是隔着杯子进行，<span style="font-family: 'Times New Roman';">n</span><span style="">杯水永远不会互相混合。</span></p>
<p>4、 热传递符合能量守恒，而且没有任何的热量损耗。</p>
<p>在这个问题里，只要求把每杯水都至少烧开一遍就可以了，而不要求最终每杯水的温度都是<span style="font-family: 'Times New Roman';">100</span><span style="">℃。我们可以用如下操作把两杯水烧开：先把一杯水加热到</span><span style="font-family: 'Times New Roman';">100</span><span style="">℃，花费能量</span><span style="font-family: 'Times New Roman';">(4200*100/2)J</span><span style="">，然后两杯水进行热传递，直到它们的温度都变成</span><span style="font-family: 'Times New Roman';">50</span><span style="">℃为止，最后把原来没有加热到</span><span style="font-family: 'Times New Roman';">100</span><span style="">℃的那杯水加热到</span><span style="font-family: 'Times New Roman';">100</span><span style="">℃，花费能量</span><span style="font-family: 'Times New Roman';">(4200*50/2)J</span><span style="">，此时两杯水都被烧开过了，当前温度一杯</span><span style="font-family: 'Times New Roman';">100</span><span style="">℃，一杯</span><span style="font-family: 'Times New Roman';">50</span><span style="">℃，花费的总能量为</span><span style="font-family: 'Times New Roman';">(4200*75)J</span><span style="">，比直接烧开所需的</span><span style="font-family: 'Times New Roman';">(4200*100)J</span><span style="">少花费了</span><span style="font-family: 'Times New Roman';">25%</span><span style="">的能量。</span></p>
<p>你的任务是设计一个最佳的操作方案使得<span style="font-family: 'Times New Roman';">n</span><span style="">杯水都至少被烧开一遍所需的总能量最少。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件只有一个数<span style="font-family: 'Times New Roman';">n</span><span style="">。</span><span style="font-family: 'Times New Roman';">(1</span><span style="">≤</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">50000)</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出<span style="font-family: 'Times New Roman';">n</span><span style="font-family: 宋体;">杯水都至少被烧开一遍所需的最少的总能量，单位为</span><span style="font-family: 'Times New Roman';">J</span><span style="font-family: 宋体;">，四舍五入到小数点后两位。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>315000.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>