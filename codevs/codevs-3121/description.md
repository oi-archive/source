<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫约翰非常认真地对待他的奶牛们的血统。然而他不是一个真正优秀的记帐员。他把他的奶牛们的家谱作成二叉树，并且把二叉树以更线性<br>的”树的中序遍历“和”树的前序遍历“的符号加以记录而不是用图形的方法。<br>你的任务是在被给予奶牛家谱的”树中序遍历“和”树前序遍历“的符号后，创建奶牛家谱的”树的后序遍历“的符号。每一头奶牛的姓名被<br>译为一个唯一的字母。（你可能已经知道你可以在知道树的两种遍历以后可以经常地重建这棵树。）显然，这里的树不会有多余26个的顶点。<br>这是在样例输入和样例输出中的树的图形表达方式：</p>
<pre>C / \ / \ B G / \ / A D H / \ E F</pre>
<p>树的中序遍历是打印左子树，根和右子树。<br>树的前序遍历是打印根，左子树和右子树。<br>树的后序遍历是打印左子树，右子树和根。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行： 树的中序遍历</span><br><span>第二行： 同样的树的前序遍历</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>单独的一行表示该树的后序遍历</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>ABEDFCHG</span><br><span>CBADEFGH</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>AEFDBHGC</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>很小</p>
</div>
</div>