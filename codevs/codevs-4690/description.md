<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>弱菜OldDirver最近在被双旋splay折磨准备轻生，请帮助可怜的OldDriver完成这道简单的题目以拯救一个鲜活的生命。</p><p><br></p><p>给定M个操作，形式为(x,y)，</p><p>如果x=1，你需要向二叉搜索树(任意节点左子树的值都小于它的值，右子树的值都大于它的值)中插入一个值y，如果它是第n个插入的，那么它的编号就是n。然后用双旋把它旋转到根，保持二叉搜索树性质不变，再输出整棵树的先根遍历（中间不必加空格）。每个节点用它的值的编号表示。</p><p>如果x=2，你需要在树中查找是否有值y，如果没有输出0，否则输出它的编号。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行会给出M。</p><p>接下来M行每行两个数x,y，空格隔开。表示一个操作(x,y)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共M行，对每个操作输出对应的一行。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10</p><p>1 76</p><p>2 67</p><p>1 676</p><p>1 8882</p><p>1 0</p><p>2 8882</p><p>1 5</p><p>1 4</p><p>1 3</p><p>1 -1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p><p>0</p><p>21</p><p>321</p><p>4312</p><p>3</p><p>54132</p><p>645132</p><p>7465132</p><p>84765132</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>M&lt;=20，所有的输入数据都是正整数且小于2^30。</p>
</div>
</div>