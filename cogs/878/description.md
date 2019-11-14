# 题目描述


USACO/heritage(<b>译 By TinyTony)
</b><div id="bodyContent"><b>
	</b><div dir="ltr" lang="zh-cn" class="mw-content-ltr"><b>
		</b><p><b>
			American Heritage</b>美国血统
		</p>
		<hr/>
	</div>
</div>
<p>
	<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
</p>
<p>
	农夫约翰非常认真地对待他的奶牛们的血统。然而他不是一个真正优秀的记帐员。他把他的奶牛们的家谱作成二叉树，并且把二叉树以更线性的“树的中序遍历”和“树的前序遍历”的符号加以记录而不是用图形的方法。
</p>
<p>
	你的任务是在被给予奶牛家谱的“树中序遍历”和“树前序遍历”的符号后，创建奶牛家谱的“树的后序遍历”的符号。每一头奶牛的姓名被译为一个唯一的字母。（你可能已经知道你可以在知道树的两种遍历以后可以经常地重建这棵树。）显然，这里的树不会有多于26个的顶点。这是在样例输入和样例输出中的树的图形表达方式：
</p>
<pre>                C
               / 
              /   
             B     G
            /    /
           A   D H
              / 
             E   F
</pre>
<p>
	树的中序遍历是按照左子树，根，右子树的顺序访问节点。
</p>
<p>
	树的前序遍历是按照根，左子树，右子树的顺序访问节点。
</p>
<p>
	树的后序遍历是按照左子树，右子树，根的顺序访问节点。
</p>
<p>
	<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
</p>
<p>
	<b>PROGRAM NAME</b>: heritage
</p>
<p>
	<b>INPUT FORMAT</b>:
</p>
<p>
	(file heritage.in)
</p>
<p>
	第一行： 树的中序遍历
</p>
<p>
	第二行： 同样的树的前序遍历
</p>
<p>
	<b>OUTPUT FORMAT</b>:
</p>
<p>
	(file heritage.out)
</p>
<p>
	单独的一行表示该树的后序遍历。
</p>
<p>
	<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT </span>
</p>
<pre>ABEDFCHG
CBADEFGH <span id="SAMPLE_OUTPUT" class="mw-headline"></span></pre>
<pre><span class="mw-headline">SAMPLE OUTPUT </span> 
<pre>AEFDBHGC
</pre>
<!-- 
NewPP limit report
Preprocessor node count: 15/1000000
Post-expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
--><!-- Saved in parser cache with key newnocow:pcache:idhash:857-0!*!*!!zh-cn!*!* and timestamp 20120711023614 --></pre>
