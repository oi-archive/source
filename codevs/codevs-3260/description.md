<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>得到一种药水有两种方法：可以按照魔法书上的指导自己配置，也可以到魔法商店里 去买——那里对于每种药水都有供应，虽然有可能价格很贵。在魔法书上有很多这样的记载： 1 份 A 药水混合 1 份 B 药水就可以得到 1 份 C 药水。 （至于为什么 1+1=1，因为……这是魔 法世界）好了，现在你知道了需要得到某种药水，还知道所有可能涉及到的药水的价格以 及魔法书上所有的配置方法，现在要问的就是：1.最少花多少钱可以配制成功这种珍贵的 药水；2.共有多少种不同的花费最少的方案（两种可行的配置方案如果有任何一个步骤不 同则视为不同的） 。假定初始时你手中并没有任何可以用的药水。怎么样才能用足够低的成 本得到 0 号药水呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有一个整数 N，表示一共涉及到的药水总数。药水从0~N-1顺序编号，0号药水 就是最终要配制的药水。</p>
<p>第二行有 N 个整数，分别表示从0~N-1顺序编号的所有药水在魔法商店的价格（都表 示1份的价格） 。</p>
<p>第三行开始，每行有 3 个整数 A、B、C，表示 1 份 A 药水混合 1 份 B 药水就可以得到 1 份 C 药水。注意，某两种特定的药水搭配如果能配成新药水的话，那么结果是唯一的。 也就是说不会出现某两行的 A、B 相同但 C 不同的情况。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出两个用空格隔开的整数， 分别表示得到0号药水的最小花费以及花费最少的方案的 个数。</p>

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
<p>10 5 6 3 2 2 3</p>
<p>1 2 0</p>
<p>4 5 1</p>
<p>3 6 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=1000 变换的方式&lt;=N^2 注意可能a,b-&gt;c的配药方式中，a=b</p>
<p>补充一下样例说明</p>
<p>最优方案有3种，分别是：直接买0号药水；买4号药水、5号药水配制成1号 药水，直接买2号药水，然后配制成0号药水；买4号药水、5号药水配制成1号药水，买3号 药水、6号药水配制成2，然后配制成0。</p>
</div>
</div>