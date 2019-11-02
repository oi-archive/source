<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">设一个<span style="font-family: DejaVu Serif Condensed,serif;">n</span>个节点的二叉树<span style="font-family: DejaVu Serif Condensed,serif;">tree</span>的中序遍历为（<span style="font-family: DejaVu Serif Condensed,serif;">l,2,3,…,n</span>），其中数字<span style="font-family: DejaVu Serif Condensed,serif;">1,2,3,…,n</span>为节点编号。每个节点都有一个分数（均为正整数），记第<span style="font-family: DejaVu Serif Condensed,serif;">j</span>个节点的分数为<span style="font-family: DejaVu Serif Condensed,serif;">di</span>，<span style="font-family: DejaVu Serif Condensed,serif;">tree</span>及它的每个子树都有一个加分，任一棵子树<span style="font-family: DejaVu Serif Condensed,serif;">subtree</span>（也包含<span style="font-family: DejaVu Serif Condensed,serif;">tree</span>本身）的加分计算方法如下：</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">subtree</span>的左子树的加分<span style="font-family: DejaVu Serif Condensed,serif;">× subtree</span>的右子树的加分＋<span style="font-family: DejaVu Serif Condensed,serif;">subtree</span>的根的分数</p>
<p style="">若某个子树为主，规定其加分为<span style="font-family: DejaVu Serif Condensed,serif;">1</span>，叶子的加分就是叶节点本身的分数。不考虑它的空</p>
<p style="">子树。</p>
<p style="">试求一棵符合中序遍历为（<span style="font-family: DejaVu Serif Condensed,serif;">1,2,3,…,n</span>）且加分最高的二叉树<span style="font-family: DejaVu Serif Condensed,serif;">tree</span>。要求输出；</p>
<p style="">（<span style="font-family: DejaVu Serif Condensed,serif;">1</span>）<span style="font-family: DejaVu Serif Condensed,serif;">tree</span>的最高加分</p>
<p style="">（<span style="font-family: DejaVu Serif Condensed,serif;">2</span>）<span style="font-family: DejaVu Serif Condensed,serif;">tree</span>的前序遍历</p>
<p> </p>
<p style=""> </p>
<p style="">现在，请你帮助你的好朋友<span style="font-family: Times New Roman,serif;">XZ</span>设计一个程序，求得正确的答案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第<span style="font-family: DejaVu Serif Condensed,serif;">1</span>行：一个整数<span style="font-family: DejaVu Serif Condensed,serif;">n</span>（<span style="font-family: DejaVu Serif Condensed,serif;">n</span>&lt;=<span style="font-family: DejaVu Serif Condensed,serif;">30</span>），为节点个数。</p>
<p style="">第<span style="font-family: DejaVu Serif Condensed,serif;">2</span>行：<span style="font-family: DejaVu Serif Condensed,serif;">n</span>个用空格隔开的整数，为每个节点的分数（分数&lt;=<span style="font-family: DejaVu Serif Condensed,serif;">100</span>）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;">第<span style="font-family: DejaVu Serif Condensed,serif;">1</span>行：一个整数，为最高加分（结果不会超过<span style="font-family: DejaVu Serif Condensed,serif;">4,000,000,000</span>）。</p>
<p style="margin-bottom: 0cm;">第<span style="font-family: DejaVu Serif Condensed,serif;">2</span>行：<span style="font-family: DejaVu Serif Condensed,serif;">n</span>个用空格隔开的整数，为该树的前序遍历。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">5</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">5 7 1 2 10</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">145</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3 1 2 4 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>n</span>（<span>n&lt;=</span><span>30)</span></p>
<p>分数&lt;=100</p>
</div>
</div>