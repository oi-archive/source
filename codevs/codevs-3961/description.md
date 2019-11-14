<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    在现实生活中，我们经常遇到硬币找零的问题，例如，在发工资时，财务人员就需要计算最少的找零硬币数，以便他们能从银行拿回最少的硬币数，并保证能用这些硬币发工资。 我们应该注意到，人民币的硬币系统是100，50，20，10，5，2，1，0.5，0.2，0.1，0.05，0.02，0.01 元，采用这些硬币我们可以对任何一个工资数用贪心算法求出其最少硬币数。但不幸的是：我们可能没有这样一种好的硬币系统，因此用贪心算法不能求出最少的硬币数，甚至有些金钱总数还不能用这些硬币找零。例如，如果硬币系统是40，30，25 元，那么37元就不能用这些硬币找零；95元的最少找零硬币数是3。又如，硬币系统是10，7，5，1元，那么12 元用贪心法得到的硬币数为3，而最少硬币数是2。 </p><p>    你的任务就是：对于任意的硬币系统和一个金钱数，请你编程求出最少的找零硬币数；如果不能用这些硬币找零，请给出一种找零方法，使剩下的钱最少。 </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第1 行，为N 和T，其中1≤N ≤50 为硬币系统中不同硬币数；1≤T≤100000 为需要用硬币找零的总数。 </p><p>    第2 行为N 个数值不大于65535 的正整数，它们是硬币系统中各硬币的面值。 </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp;&nbsp;如T 能被硬币系统中的硬币找零，请输出最少的找零硬币数。&nbsp;</p><p>&nbsp; &nbsp; 如T 不能被硬币系统中的硬币找零，请输出剩下钱数最少的找零方案中的最少硬币数。&nbsp;</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>    4 12 </p><p>    10 7 5 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>    2<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>青铜水题</p>
</div>
</div>