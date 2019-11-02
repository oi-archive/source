<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<pre>　　郑厂长不是正厂长<br>　　也不是副厂长<br>　　他根本就不是厂长<br>　　只是公司的一个码农<br>　　<br>　　郑厂长所在的公司每一年都要组织员工体检，比如量身高体重、测血压之类的，今年也不例外。<br>　　这次总共有N位员工接受体检，并且每个员工都需要做K个项目的检查才算完成整个体检的流程。现在来了M个医生为员工做身体检查，并且每一位医生都带齐了检查这K个项目的器材来(也就是说每个医生都能进行这K个项目中的任意一项检查)。<br>　　体检的详细流程是这样的：<br>　　公司事先制定好了M份体检单，每个医生手上都各自拿到一份体检单，上面已经安排好了检查的次序，以及每一次检查所对应的员工和项目。每个医生按照体检单上的次序为相应的员工做相应的项目检查。医生拿到的体检单上的名单也可以是空的，就是这个医生不需要检查任何员工的任何项目。<br>　　当然，制定出的这M份体检单不能有问题存在，否则就会有混乱的情况发生。按照常理来说，同一个医生在同一时间只能为一个员工做一个项目的检查。另外，同一个员工在同一时间也只能进行一个项目的检查，当然，不同的医生或不同的员工可以在同一时间进行项目检查。现在假设每个员工的每个项目的检查时间都是一分钟（其它时间花费忽略不计，只考虑项目检查工作所花费的一分钟)。<br>　　公司希望体检的工作越快完成越好，由于郑厂长大学期间曾经是一个ACMer，所以公司就将体检的安排工作交给了他，他需要计算出最快需要多少分钟能完成所有员工的体检工作。</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<pre>输入的第一行为一个正整数T，表示有T组测试数据；<br>接下去有T组测试数据，每组测试数据占一行，包含三个整数N，K，M，N表示员工的人数，K表示体检的项目数，M表示医生的人数。<br><br><strong>[Technical Specification]</strong><br>T&lt;=1000<br>1&lt;=N&lt;=100<br>1&lt;=K&lt;=10<br>1&lt;=M&lt;=100</pre>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<pre>对于每组数据，输出一个整数，表示最快需要多少分钟才能完成所有员工的体检工作。</pre>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>2
2 1 1
3 2 2</pre>

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
<pre>对于第二组数据体检单的安排可以是如下情况：
第1个医生的体检单：员工A的项目1、员工A的项目2、员工B的项目2；
第2个医生的体检单：员工B的项目1、员工C的项目1、员工C的项目2。
第一分钟：第1个医生检查员工A的项目1，而第2个医生检查员工B的项目1；
第二分钟：第1个医生检查员工A的项目2，而第2个医生检查员工C的项目1；
第三分钟：第1个医生检查员工B的项目2，而第2个医生检查员工C的项目2；
这样就只需要3分钟即可完成体检工作。
</pre>
</div>
</div>