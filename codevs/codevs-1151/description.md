<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>世博会志愿者的选拔工作正在 A 市如火如荼的进行。为了选拔最合适的人才，A 市对所有报名的选手进行了笔试，笔试分数达到面试分数线的选手方可进入面试。面试分数线根据计划录取人数的150%划定，即如果计划录取m名志愿者，则面试分数线为排名第m*150%（向下取整）名的选手的分数，而最终进入面试的选手为笔试成绩不低于面试分数线的所有选手。<br>现在就请你编写程序划定面试分数线，并输出所有进入面试的选手的报名号和笔试成绩。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，两个整数n，m（5 ≤ n ≤ 5000，3 ≤ m ≤ n），中间用一个空格隔开，其中n 表示报名参加笔试的选手总数，m 表示计划录取的志愿者人数。输入数据保证m*150%向下取整后小于等于n。<br>第二行到第 n+1 行，每行包括两个整数，中间用一个空格隔开，分别是选手的报名号k（1000 ≤ k ≤ 9999）和该选手的笔试成绩s（1 ≤ s ≤ 100）。数据保证选手的报名号各不相同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行，有两个整数，用一个空格隔开，第一个整数表示面试分数线；第二个整数为进入面试的选手的实际人数。<br />从第二行开始，每行包含两个整数，中间用一个空格隔开，分别表示进入面试的选手的报名号和笔试成绩，按照笔试成绩从高到低输出，如果成绩相同，则按报名号由小到大的顺序输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 3<br>1000 90<br>3239 88<br>2390 95<br>7231 84<br>1005 95<br>1001 88</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>88 5<br>1005 95<br>2390 95<br>1000 90<br>1001 88<br>3239 88</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>m*150% = 3*150% = 4.5，向下取整后为4。保证4 个人进入面试的分数线为88，但因为88有重分，所以所有成绩大于等于88 的选手都可以进入面试，故最终有5 个人进入面试。</p>
</div>
</div>