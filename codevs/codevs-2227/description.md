<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>        这次小可可想解决的难题和中国象棋有关，在一个N行M列的棋盘上，让你放若干个炮（可以是0个），使得没有一个炮可以攻击到另一个炮，请问有多少种放置方法。大家肯定很清楚，在中国象棋中炮的行走方式是：一个炮攻击到另一个炮，当且仅当它们在同一行或同一列中，且它们之间恰好 有一个棋子。你也来和小可可一起锻炼一下思维吧！<br> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行包含两个整数N，M，之间由一个空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>总共的方案数，由于该值可能很大，只需给出方案数模9999973的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>样例说明</strong></p>
<p>除了3个格子里都塞满了炮以外，其它方案都是可行的，所以一共有2*2*2-1=7种方案。</p>
<p><strong>数据范围</strong></p>
<p>100%的数据中N和M均不超过100<br>  50%的数据中N和M至少有一个数不超过8<br>  30%的数据中N和M均不超过6</p>
</div>
</div>