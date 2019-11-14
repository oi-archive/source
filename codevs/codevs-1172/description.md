<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Hanks 博士是BT (Bio-Tech，生物技术) 领域的知名专家，他的儿子名叫Hankson。现<br>在，刚刚放学回家的Hankson 正在思考一个有趣的问题。<br>今天在课堂上，老师讲解了如何求两个正整数c1 和c2 的最大公约数和最小公倍数。现<br>在Hankson 认为自己已经熟练地掌握了这些知识，他开始思考一个“求公约数”和“求公<br>倍数”之类问题的“逆问题”，这个问题是这样的：已知正整数a0,a1,b0,b1，设某未知正整<br>数x 满足：<br>1． x 和a0 的最大公约数是a1；<br>2． x 和b0 的最小公倍数是b1。<br>Hankson 的“逆问题”就是求出满足条件的正整数x。但稍加思索之后，他发现这样的<br>x 并不唯一，甚至可能不存在。因此他转而开始考虑如何求解满足条件的x 的个数。请你帮<br>助他编程求解这个问题。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个正整数n，表示有n 组输入数据。接下来的n 行每<br>行一组输入数据，为四个正整数a0，a1，b0，b1，每两个整数之间用一个空格隔开。输入<br>数据保证a0 能被a1 整除，b1 能被b0 整除。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每组输入数据的输出结果占一行，为一个整数。<br />对于每组数据：若不存在这样的 x，请输出0；<br />若存在这样的 x，请输出满足条件的x 的个数；</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>41 1 96 288<br>95 1 37 1776</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【说明】<br>第一组输入数据，x 可以是9、18、36、72、144、288，共有6 个。<br>第二组输入数据，x 可以是48、1776，共有2 个。<br>【数据范围】<br>对于 50%的数据，保证有1≤a0，a1，b0，b1≤10000 且n≤100。<br>对于 100%的数据，保证有1≤a0，a1，b0，b1≤2,000,000,000 且n≤2000。</p>
</div>
</div>