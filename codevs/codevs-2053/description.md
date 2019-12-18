<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农民约翰准备购买一群新奶牛。 在这个新的奶牛群中, 每一个母亲奶牛都生两个小奶牛。这些奶牛间的关系可以用二叉树来表示。这些二叉树总共有N个节点(3 &lt;= N &lt; 200)。这些二叉树有如下性质:</p>
<p>每一个节点的度是0或2。度是这个节点的孩子的数目。</p>
<p><br>树的高度等于K(1 &lt; K &lt; 100)。高度是从根到最远的那个叶子所需要经过的结点数; 叶子是指没有孩子的节点。</p>
<p> </p>
<p>有多少不同的家谱结构? 如果一个家谱的树结构不同于另一个的, 那么这两个家谱就是不同的。输出可能的家谱树的个数除以9901的余数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第1行: 两个空格分开的整数, N和K。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>第 1 行: 一个整数，表示可能的家谱树的个数除以9901的余数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p>

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
<p>有5个节点，高为3的两个不同的家谱：</p>
<pre>           @                                @
/ \                                /  \
@ @        和                  @  @
/ \                                 / \
@   @                          @   @</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>