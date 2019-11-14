# 题目描述


<h3>
【题目描述】
</h3>
<p>
我们可以把由“<span>0</span><span>”和“</span><span>1</span><span>”组成的字符串分为三类：全“</span><span>0</span><span>”串称为</span><span>B</span><span>串，全“</span><span>1</span><span>”串称为</span><span>I</span><span>串，既含“</span><span>0</span><span>”又含“</span><span>1</span><span>”的串则称为</span><span>F</span><span>串。</span> 
</p>
<p>
FBI<span>树是一种二叉树</span><span></span><span>，它的结点类型也包括</span><span>F</span><span>结点，</span><span>B</span><span>结点和</span><span>I</span><span>结点三种。由一个长度为</span><span>2N</span><span>的“</span><span>01</span><span>”串</span><span>S</span><span>可以构造出一棵</span><span>FBI</span><span>树</span><span>T</span><span>，递归的构造方法如下：</span> 
</p>
<p>
1)      T<span>的根结点为</span><span>R</span><span>，其类型与串</span><span>S</span><span>的类型相同；</span> 
</p>
<p>
2)      <span>若串</span><span>S</span><span>的长度大于</span><span>1</span><span>，将串</span><span>S</span><span>从中间分开，分为等长的左右子串</span><span>S1</span><span>和</span><span>S2</span><span>；由左子串</span><span>S1</span><span>构造</span><span>R</span><span>的左子树</span><span>T1</span><span>，由右子串</span><span>S2</span><span>构造</span><span>R</span><span>的右子树</span><span>T2</span><span>。</span> 
</p>
<p>
现在给定一个长度为<span>2^N</span><span>的“</span><span>01</span><span>”串，请用上述构造方法构造出一棵</span><span>FBI</span><span>树，并输出它的后序遍历</span><span></span><span>序列。</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件<span>的第一行是一个整数</span><span>N</span><span>（</span><span>0 &lt;= N &lt;= 10</span><span>），第二行是一个长度为</span><span>2^N</span><span>的“</span><span>01</span><span>”串。</span> 
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件<span>包括一行，这一行只包含一个字符串，即</span><span>FBI</span><span>树的后序遍历序列。</span> 
</p>
<h3>
【样例输入】
</h3>
<pre>3
10001011</pre>
<h3>
【样例输出】
</h3>
<pre>IBFBBBFIBFIIIFF</pre>
<h3>
【数据规模】
</h3>
<p>
对于40%的数据，N &lt;= 2；
</p>
<p>
对于全部的数据，N &lt;= 10。
</p>
