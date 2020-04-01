<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Stupid 家族得知在HYC家的后花园里的中央花坛处,向北走3步,向西走3步,再向北走3步,向东走3步,再向北走6步,向东走3步,向南走12步,再向西走2步( - -||)就能找到宝藏的入口,而且宝藏都是藏在山里的,必须挖出来,于是Stupid家族派狗狗带领矿工队去挖宝藏.(HYC家的宝藏被狗狗挖走后有什么感想?)</p>
<p> </p>
<p>这个宝藏的制造者为了掩盖世人耳目,他做的宝藏是没有出口,只有入口,不少建造宝藏的人都死在里面.现在知道宝藏总共有N个分岔口,在分岔口处是有财宝的,每个宝藏点都有一个财富值.狗狗只带了M个人来,而且为了安全起见,在每个分岔口,必须至少留一个人下来,这个留下来的人可以挖宝藏(每个人只能挖一个地方的宝藏),这样才能保证不会迷路,而且这个迷宫有个特点,任意两点间有且只有一条路可通.狗狗为了让他的00开心,决定要尽可能地多挖些宝藏回去.现在狗狗的圈叉电脑不在身旁,只能求救于你了,你要知道,狗狗的终身幸福就在你手上了..（狗狗ps：00，你不能就这样抛弃偶……）</p>
<p><strong>数据范围</strong></p>
<p>对于10%的数据，n&lt;10</p>
<p>对于100%的数据，n&lt;=1000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：两个正整数N,M .N表示宝藏点的个数,M表示狗狗带去的人数(那是一条懒狗,他自己可不做事)。(m&lt;=100)</p>
<p>第2行：N个整数,第i个整数表示第i个宝藏的财富值.(保证|wi|&lt;maxint)</p>
<p>第N+2行：两个非负整数A和B，表示A通向B,当A=0,表示A是入口.（保证A,B&lt;=n）</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出狗狗能带回去的宝藏的价值。</p>

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
<p>5 6 2 4</p>
<p>1 2</p>
<p>0 1</p>
<p>2 3</p>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p>

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