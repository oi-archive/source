<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个无向连通图，其节点编号为1到N，其边的权值为非负整数。试求出一条从1号节点到 N 号节点的路径，使得该路径上经过的边的权值的“XOR 和”最大。该路径可以重复经过某些节点或边，当一条边在路径中出现多次时，其权值在计算“XOR 和”时也要被重复计算相应多的次数。</p>
<p>直接求解上述问题比较困难，于是你决定使用非完美算法。具体来说，从1号节点开始，以相等的概率，随机选择与当前节点相关联的某条边，并沿这条边走到下一个节点，重复这个过程，直到走到N号节点为止，便得到一条从1号节点到N号节点的路径。显然得到每条这样的路径的概率是不同的并且每条这样的路径的“XOR 和”也不一样。现在请你求出该算法得到的路径的“XOR和”的期望值。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是用空格隔开的两个正整数N和M，分别表示该图的节点数和边数。紧接着的M行，每行是用空格隔开的三个非负整数u，v和w(1≤u,v≤N， 0≤w≤10<sup>9</sup>)，表示该图的一条边(u,v)，其权值为w。输入的数据保证图连通，30%的数据满足N≤30，100%的数据满足2≤N≤100，M≤10000，但是图中可能有重边或自环。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个实数，表示上述算法得到的路径的&ldquo;XOR和&rdquo;的期望值，要求保留三位小数。（建议使用精度较高的数据类型进行计算）&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2<br>1 1 2<br>1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2.333</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：有1/2的概率直接从1号节点走到2号节点，该路径的“XOR和”为3；有1/4的概率从1号节点走一次1号节点的自环后走到2号节点，该路径的“XOR和”为1；有1/8的概率从1号节点走两次1号节点的自环后走到2号节点，该路径的“XOR和”为3；......；依此类推，可知“XOR和”的期望值为：3/2+1/4+3/8+1/16+3/32+....=7/3，约等于2.333。</p>
<p> </p>
<p>数据范围如题</p>
</div>
</div>