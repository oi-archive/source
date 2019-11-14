<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现给出一棵N个结点二叉树，问这棵二叉树中最长链的长度为多少，保证了1号结点为二叉树的根。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第1行为包含了一个正整数N，为这棵二叉树的结点数，结点标号由1至N。</p>
<p>接下来N行，这N行中的第i行包含两个正整数l[i], r[i]，表示了结点i的左儿子与右儿子编号。如果l[i]为0，表示结点i没有左儿子，同样地，如果r[i]为0则表示没有右儿子。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包括1个正整数，为这棵二叉树的最长链长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>2 3</p>
<p>4 5</p>
<p>0 6</p>
<p>0 0</p>
<p>0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>　　4-2-1-3-6为这棵二叉树中的一条最长链。</p>
<p> </p>
<p>【数据规模】</p>
<p>对于10%的数据，有N≤10；</p>
<p>对于40%的数据，有N≤100；</p>
<p>对于50%的数据，有N≤1000；</p>
<p>对于60%的数据，有N≤10000；</p>
<p>对于100%的数据，有N≤100000，且保证了树的深度不超过32768。</p>
<p> </p>
<p>【提示】</p>
<p><strong>关于二叉树：</strong></p>
<p>二叉树的递归定义：二叉树要么为空，要么由根结点，左子树，右子树组成。左子树和右子树分别是一棵二叉树。</p>
<p>请注意，有根树和二叉树的三个主要差别：</p>
<p>1. 树的结点个数至少为1，而二叉树的结点个数可以为0；</p>
<p>2. 树中结点的最大度数没有限制，而二叉树结点的最大度数为2；</p>
<p>3. 树的结点无左、右之分，而二叉树的结点有左、右之分。</p>
<p><strong>关于最长链：</strong></p>
<p>最长链为这棵二叉树中一条最长的简单路径，即不经过重复结点的一条路径。可以容易证明，二叉树中最长链的起始、结束结点均为叶子结点。</p>
<p> </p>
</div>
</div>