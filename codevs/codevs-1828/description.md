<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在，保密成为一个很重要也很困难的问题。如果没有做好，后果是严重的。比如，有个人没有自己去修电脑，又没有拆硬盘，后来的事大家都知道了。</p>
<p>当然，对保密最需求的当然是军方，其次才是像那个人。为了应付现在天上飞来飞去的卫星，军事基地一般都会建造在地下。</p>
<p>某K国的军事基地是这样子的：地面上两排大天井共n1个作为出入口，内部是许多除可以共享出入口外互不连通的空腔，每个空腔有且只有两个出入口，并且这两个出入口不会在同一排。为了方便起见，两排出入口分别编号为1,3,5…和2,4,6…并且最大的编号为n1。</p>
<p>虽然上面扯了那么多关于保密的东西，但是其实解密也是一件很纠结的事情。但其实最简单直接暴力无脑的解密方法就是找个人去看看。。。</p>
<p>我们有很牛X的特种部队，只需要派出一支特种部队到K国基地的某个出入口，那么和这个出入口直接相连的所有空腔都可以被探索，但也只有这些空腔可以被这支部队探索。现在有足够多的特种部队可以供你调遣，你必须使用他们调查完所有的K国基地内的空腔。</p>
<p>当然，你的基地离<span style="font-family: 'Times New Roman';">K</span><span style="">国基地不会太近，周边的地图将会给你，表示为</span><span style="font-family: 'Times New Roman';">n</span><span style="">个检查点和</span><span style="font-family: 'Times New Roman';">m</span><span style="">条连接这些点的道路，其中点</span><span style="font-family: 'Times New Roman';">1</span><span style="">到点</span><span style="font-family: 'Times New Roman';">n1</span><span style="">就是</span><span style="font-family: 'Times New Roman';">K</span><span style="">国基地的出入口，点</span><span style="font-family: 'Times New Roman';">n</span><span style="">是你的部队的出发点。对每条道路，有不同的通行时间</span><span style="font-family: 'Times New Roman';">t</span><span style="">和安全系数</span><span style="font-family: 'Times New Roman';">s</span><span style="">。因为情报部门只对单向的道路安全系数进行了评估，所以这些道路只允许单向通行，并且不会存在环。</span></p>
<p>一支特种部队从你的基地出发，通过某条路径，到达某个<span style="font-family: 'Times New Roman';">K</span><span style="">国基地出入口，此时这支部队的危险性表示为总时间和这条路径经过的所有道路的安全系数和的比值。整个行动的危险性表示为你派出的所有部队的危险性之和。你需要使这个值最小的情况下探索整个</span><span style="font-family: 'Times New Roman';">K</span><span style="">国基地。</span></p>
<p>快点完成这个任务，在<span style="font-family: 'Times New Roman';">K</span><span style="">国的叫兽宣布你是</span><span style="font-family: 'Times New Roman';">K</span><span style="">国人之前。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行<span style="font-family: 'Times New Roman';">2</span><span style="">个正整数</span><span style="font-family: 'Times New Roman';">n</span><span style="">，</span><span style="font-family: 'Times New Roman';">m (4 &lt;= n &lt;= 700, m &lt;= 100000) </span><span style="">表示整个地区地图上的检查点和道路数。</span></p>
<p>下面<span style="font-family: 'Times New Roman';">m</span><span style="">行，每行</span><span style="font-family: 'Times New Roman';">4</span><span style="">个正整数</span><span style="font-family: 'Times New Roman';">a, b, t, s(a, b &lt;=n, 1 &lt;= t, s &lt;= 10)</span><span style="">表示一条从</span><span style="font-family: 'Times New Roman';">a</span><span style="">到</span><span style="font-family: 'Times New Roman';">b</span><span style="">的道路需时为</span><span style="font-family: 'Times New Roman';">t</span><span style="">，安全系数为</span><span style="font-family: 'Times New Roman';">s</span><span style="">。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">1</span><span style="">行</span><span style="font-family: 'Times New Roman';">2</span><span style="">个正整数</span><span style="font-family: 'Times New Roman';">m1</span><span style="">和</span><span style="font-family: 'Times New Roman';">n1(m1 &lt;= 40000, n1 &lt; min{n, 161}), m1</span><span style="">表示</span><span style="font-family: 'Times New Roman';">K</span><span style="">国基地空腔的个数，</span><span style="font-family: 'Times New Roman';">n1</span><span style="">表示</span><span style="font-family: 'Times New Roman';">K</span><span style="">国基地出入口的个数。</span></p>
<p>再接下来<span style="font-family: 'Times New Roman';">m1</span><span style="">行，每行</span><span style="font-family: 'Times New Roman';">2</span><span style="">个正整数</span><span style="font-family: 'Times New Roman';">u, v (u, v&lt;=n1, u</span><span style="">是奇数，</span><span style="font-family: 'Times New Roman';">v</span><span style="">是偶数</span><span style="font-family: 'Times New Roman';">)</span><span style="">，表示每个空腔的</span><span style="font-family: 'Times New Roman';">2</span><span style="">个出入口。  </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一行，最小的危险性，保留一位小数。或者输出<span style="font-family: 'Times New Roman';">&rdquo;-1&rdquo;</span><span style="font-family: 宋体;">（无引号）表示此任务不可能完成。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p>
<p>5 1 10 1</p>
<p>5 1 10 1</p>
<p>5 2 9 1</p>
<p>5 3 7 1</p>
<p>5 4 8 1</p>
<p>4 4</p>
<p>1 2</p>
<p>1 4</p>
<p>3 2</p>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>17.0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n&lt;=30</span></p>
<p>对<span style="font-family: 'Times New Roman';">60%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n&lt;=300</span></p>
<p> </p>
<p>另外 <span style="font-family: 'Times New Roman';">40%</span><span style="">的数据</span><span style="font-family: 'Times New Roman';">n1&lt;=20</span></p>
<p> </p>
</div>
</div>