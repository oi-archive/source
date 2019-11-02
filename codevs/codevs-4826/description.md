<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小N最近在研究NP完全问题，小O看小N研究得热火朝天，便给他出了一道这样的题目：</p><p><br></p><p>有n个球，用整数1到n编号。还有m个筐子，用整数1到m编号。</p><p><br></p><p>每个球只能放进特定的两个筐子之一，第i个球可以放进的框子记为Ai和Bi。</p><p><br></p><p>每个球都必须放进一个筐子中。如果一个筐子内有奇数个球，那么我们称这样的筐子为半空的。</p><p><br></p><p>求半空的筐子最少有多少个</p><p><br></p><p>小N看到题目后瞬间没了思路，站在旁边看热闹的小I嘿嘿一笑：“水题！”</p><p><br></p><p>然后三言两语道出了一个多项式算法。</p><p><br></p><p>小N瞬间就惊呆了，三秒钟后他回过神来一拍桌子：</p><p><br></p><p>“不对！这个问题显然是NP完全问题，你算法肯定有错！”</p><p><br></p><p>小I浅笑：“所以，等我领图灵奖吧!”</p><p><br></p><p>小O只会出题不会做题，所以找到了你——请你对这个问题进行探究，并写一个程序解决此题。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数N，M</p><p><br></p><p>接下来N行，第i+1行有两个整数Ai,Bi，表示第i个球可以放的两个筐子，保证Ai 不等于 Bi</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数表示在半空的筐子的最小值</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3</p><p>1 2</p><p>2 3</p><p>1 3</p><p>1 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><br></p><p>【样例解释】</p><p>1,3号球都放在1号筐子，2,4号球都放在2号筐子工作</p><p><br></p><p><br></p><p>对于30%的数据，$1 \leq N,M \leq 15$</p><p>对于另外10%的数据,$1 \leq N,M \leq 100$</p><p>对于另外10%的数据，每个球都能放在1号筐子</p><p>对于另外10%的数据，$N \leq M - 1$，第i个球可以放的筐子是第i个筐子和第i + 1个筐子</p><p>对于100%的数据，$1 \leq N,M \leq 2 \times 10^5$</p><p><br></p>
</div>
</div>