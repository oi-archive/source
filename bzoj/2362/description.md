
# Description

<div class="content"><div align="center"><b> </b></div>
<div style="text-indent: 20.25pt" align="left">在那个植树节，晚上，小L，小H，小X讨论起了一个关于树的问题：</div>
<div style="text-indent: 20.25pt" align="left">有多少个不同的二叉树最长链为<i>N</i>。</div>
<div style="text-indent: 20.25pt" align="left">但是他们发现，答案随<i>N</i>增长的速度太快了，他们想不出什么好方法，便求助于你。</div>
<div style="text-indent: 20.25pt" align="left">由于答案可能会很大，你只需要输出答案mod 10<i><sup>K</sup></i>后的结果即可。</div></div>

# Input

<div class="content"><div align="left">包含两个正整数<i>N</i>，<i>K</i>。表示询问有多少个不同的二叉树最长链为<i>N</i>。</div>
<div style="text-indent: 20.25pt" align="left"> </div>
<div align="left"></div></div>

# Output

<div class="content"><div align="left">包含一个非负整数，为答案mod 10<i><sup>K</sup></i>后的结果。</div>
<div align="left"> </div>
<div style="text-indent: 20.25pt" align="left"></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 10<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，有N≤200000，K≤64；<br/><br/>
 <br/><br/>
【提示】<br/><br/>
关于二叉树：<br/><br/>
二叉树的递归定义：二叉树要么为空，要么由根结点，左子树，右子树组成。左子树和右子树分别是一棵二叉树。<br/><br/>
请注意，有根树和二叉树的三个主要差别：<br/><br/>
1. 树的结点个数至少为1，而二叉树的结点个数可以为0；<br/><br/>
2. 树中结点的最大度数没有限制，而二叉树结点的最大度数为2；<br/><br/>
3. 树的结点无左、右之分，而二叉树的结点有左、右之分。<br/><br/>
关于最长链：<br/><br/>
最长链为这棵二叉树中一条最长的简单路径，即不经过重复结点的一条路径。可以容易证明，二叉树中最长链的起始、结束结点均为叶子结点。<br/><br/>
 </p><br/>
<p><br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

