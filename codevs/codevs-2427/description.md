<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>斜堆(skew heap)是一种常用的数据结构。它也是二叉树，且满足与二叉堆相同的堆性质：每个非根结点的值都比它父亲大。因此在整棵斜堆中，根的值最小。但斜堆不必是平衡的，每个结点的左右儿子的大小关系也没有任何规定。在本题中，斜堆中各个元素的值均不相同。 在斜堆H中插入新元素X的过程是递归进行的：当H为空或者X小于H的根结点时X变为新的树根，而原来的树根（如果有的话）变为X的左儿子。当X大于H的根结点时，H根结点的两棵子树交换，而X（递归）插入到交换后的左子树中。 给出一棵斜堆，包含值为0~n的结点各一次。求一个结点序列，使得该斜堆可以通过在空树中依次插入这些结点得到。如果答案不惟一，输出字典序最小的解。输入保证有解。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行包含一个整数n。第二行包含n个整数d1, d2, ... , dn， di&lt;100表示i是di的左儿子，di&gt;=100表示i是di-100的右儿子。显然0总是根，所以输入中不含d0。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅一行，包含n+1整数，即字典序最小的插入序列。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6</span><br><span> 100 0 101 102 1 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>0 1 2 3 4 5 6</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2 &lt;= n &lt;= 50 </p>
</div>
</div>