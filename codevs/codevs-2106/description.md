<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近IK正在做关于地形建模的工作。其中一个工作阶段就是把一些山排列成一行。每座山都有各不相同的标号和高度。为了遵从一些设计上的要求，每座山都设置了一个关键数字，要求对于每座山，比它高且排列在它前面的其它山的数目必须少于它的关键数字。</p>
<p>显然满足要求的排列会有很多个。对于每一个可能的排列，IK生成一个对应的标号序列和等高线序列。标号序列就是按顺序写下每座山的标号。等高线序列就是按顺序写下它们的高度。例如有两座山，这两座山的一个合法排列的第一座山的标号和高度为1和3，而第二座山的标号和高度分别为2和4，那么这个排列的标号序列就是1 2，而等高线序列就是3 4.</p>
<p>现在问题就是，给出所有山的信息，IK希望知道一共有多少种不同的符合条件的标号序列和等高线序列。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行给出山的个数N。接下来N行每行有两个整数，按照标号从1到N的顺序分别给出一座山的高度和关键数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出两个用空格分隔开的数，第一个数是不同的标号序列的个数，第二个数是不同的等高线序列的个数。这两个答案都应该对2011取模，即输出两个答案除以2011取余数的结果</p>

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
<p>1 2</p>
<p>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，有1&lt;=N&lt;=10.</p>
<p>对于所有的数据，有1&lt;=N&lt;=1000，所有的数字都是不大于10<sup>9</sup>的正整数。</p>
</div>
</div>