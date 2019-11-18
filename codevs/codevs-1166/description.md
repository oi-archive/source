<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【问题描述】<br>帅帅经常跟同学玩一个矩阵取数游戏：对于一个给定的n*m 的矩阵，矩阵中的每个元素aij均<br>为非负整数。游戏规则如下：<br>1. 每次取数时须从每行各取走一个元素，共n个。m次后取完矩阵所有元素；<br>2. 每次取走的各个元素只能是该元素所在行的行首或行尾；<br>3. 每次取数都有一个得分值，为每行取数的得分之和，每行取数的得分= 被取走的元素值*2<sup>i</sup>，<br>其中i 表示第i 次取数（从1 开始编号）；<br>4. 游戏结束总得分为m次取数得分之和。<br>帅帅想请你帮忙写一个程序，对于任意矩阵，可以求出取数后的最大得分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行为两个用空格隔开的整数n和m。<br>第2~n+1 行为n*m矩阵，其中每行有m个用单个空格隔开的非负整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出 仅包含1 行，为一个整数，即输入矩阵取数后的最大得分。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3<br>1 2 3<br>3 4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>82</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释</p>
<p>第 1 次：第1 行取行首元素，第2 行取行尾元素，本次得分为1*2<sup>1</sup>+2*2<sup>1</sup>=6<br>第2 次：两行均取行首元素，本次得分为2*2<sup>2</sup>+3*2<sup>2</sup>=20<br>第3 次：得分为3*2<sup>3</sup>+4*2<sup>3</sup>=56。总得分为6+20+56=82</p>
<p> </p>
<p>【限制】<br>60%的数据满足：1&lt;=n, m&lt;=30, 答案不超过10<sup>16</sup><br>100%的数据满足：1&lt;=n, m&lt;=80, 0&lt;=aij&lt;=1000</p>
</div>
</div>