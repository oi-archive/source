<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Mars</span></span></span></span><span style="">星球上，每个</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Mars</span></span></span></span><span style="">人都随身佩带着一串能量项链。在项链上有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">颗能量珠。能量珠是一颗有头标记与尾标记的珠子，这些标记对应着某个正整数。并且，对于相邻的两颗珠子，前一颗珠子的尾标记一定等于后一颗珠子的头标记。因为只有这样，通过吸盘（吸盘是</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Mars</span></span></span></span><span style="">人吸收能量的一种器官）的作用，这两颗珠子才能聚合成一颗珠子，同时释放出可以被吸盘吸收的能量。如果前一颗能量珠的头标记为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">，尾标记为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">r</span></span></span></span><span style="">，后一颗能量珠的头标记为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">r</span></span></span></span><span style="">，尾标记为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n</span></span></span></span><span style="">，则聚合后释放的能量为m*r*n（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Mars</span></span></span></span><span style="">单位），新产生的珠子的头标记为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">，尾标记为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n</span></span></span></span><span style="">。</span></p>
<p style=""><span style="">需要时，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Mars</span></span></span></span><span style="">人就用吸盘夹住相邻的两颗珠子，通过聚合得到能量，直到项链上只剩下一颗珠子为止。显然，不同的聚合顺序得到的总能量是不同的，请你设计一个聚合顺序，使一串项链释放出的总能量最大。</span></p>
<p style=""><span style="">例如：设</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N=4</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">4</span></span></span></span><span style="">颗珠子的头标记与尾标记依次为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">(2</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3) (3</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">5) (5</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">10) (10</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2)</span></span></span></span><span style="">。我们用记号⊕表示两颗珠子的聚合操作，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">(j</span><span style="">⊕</span><span style="font-family: Courier New,monospace;">k)</span></span></span></span><span style="">表示第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k</span></span></span></span><span style="">两颗珠子聚合后所释放的能量。则第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">4</span></span></span></span><span style="">、</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">两颗珠子聚合后释放的能量为：</span></p>
<p style=""><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">(4</span><span style="">⊕</span><span style="font-family: Courier New,monospace;">1)=10*2*3=60</span></span></span></span><span style="">。</span></p>
<p style=""><span style="">这一串项链可以得到最优值的一个聚合顺序所释放的总能量为</span></p>
<p style=""><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">((4</span><span style="">⊕</span><span style="font-family: Courier New,monospace;">1)</span><span style="">⊕</span><span style="font-family: Courier New,monospace;">2)</span><span style="">⊕</span><span style="font-family: Courier New,monospace;">3</span></span></span></span><span style="">）</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">=10*2*3+10*3*5+10*5*10=710</span></span></span></span><span style="">。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行是一个正整数</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">4</span><span style="">≤</span><span style="font-family: Courier New,monospace;">N</span><span style="">≤</span><span style="font-family: Courier New,monospace;">100</span></span></span></span><span style="">），表示项链上珠子的个数。第二行是</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">个用空格隔开的正整数，所有的数均不超过</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1000</span></span></span></span><span style="">。第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">i</span></span></span></span><span style="">个数为第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">i</span></span></span></span><span style="">颗珠子的头标记（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span><span style="">≤</span><span style="font-family: Courier New,monospace;">i</span><span style="">≤</span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">），当</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">i&lt;N&lt; span&gt;</span></span></span></span><span style="">时，第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">i</span></span></span></span><span style="">颗珠子的尾标记应该等于第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">i+1</span></span></span></span><span style="">颗珠子的头标记。第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">颗珠子的尾标记应该等于第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">颗珠子的头标记。</span></p>
<p style=""><span style="">至于珠子的顺序，你可以这样确定：将项链放到桌面上，不要出现交叉，随意指定第一颗珠子，然后按顺时针方向确定其他珠子的顺序。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="text-indent: 0.74cm; margin-top: 0.49cm; margin-bottom: 0.49cm; line-height: 0.64cm; widows: 2; orphans: 2;" align="LEFT"><span style="font-size: small;">只有一行，是一个正整数</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">E</span></span></span></span><span style="font-size: small;">（</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">E</span><span style="font-family: 宋体,SimSun;">&le;</span><span style="font-family: Courier New,monospace;">2.1*10</span><sup><span style="font-family: Courier New,monospace;">9</span></sup></span></span></span><span style="font-size: small;">），为一个最优聚合顺序所释放的总能量。</span></p>

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
<p>2 3 5 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>710</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>