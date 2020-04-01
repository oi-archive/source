
# Description

<div class="content"><div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">一日ll给dd讲解二叉树的知识：</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><b><span style="font-size: 12pt; line-height: 150%">二叉树t是单个节点或有序对t=(t1,t2)，其中t1是t的左子树，t2是t的右子树，满足t1、t2都是二叉树</span></b></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">定义一种大小比较关系：</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">1. </span><span style="font-size: 12pt; line-height: 150%">单个节点≤t</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">2. (u1,u2)</span><span style="font-size: 12pt; line-height: 150%">≤(v1,v2)，当且仅当u1&lt;v1，或u1=v1且u2≤v2</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">t</span><span style="font-size: 12pt; line-height: 150%">的后继t</span><span style="font-size: 12pt; line-height: 150%">’</span><span style="font-size: 12pt; line-height: 150%">为所有大小为|t|的二叉树中，大于t的最小的二叉树(若t是最大的，则t</span><span style="font-size: 12pt; line-height: 150%">’</span><span style="font-size: 12pt; line-height: 150%">为最小的)</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">ll</span><span style="font-size: 12pt; line-height: 150%">道：“找出t的后继t</span><span style="font-size: 12pt; line-height: 150%">’</span><span style="font-size: 12pt; line-height: 150%">，就算你及格了”</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">dd</span><span style="font-size: 12pt; line-height: 150%">想了想，给出了答案</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">正当ll准备表扬dd时，dd道：“不如把问题变复杂一点吧！”</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">定义函数f：</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">1. f(</span><span style="font-size: 12pt; line-height: 150%">单个节点)=0</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">2. f((t1,t2)) = 2^(|t1|+|t2|) + 2^|t2|*f(t1) + f(t2)</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">“现在给出f(t)，求f(t</span><span style="font-size: 12pt; line-height: 150%">’</span><span style="font-size: 12pt; line-height: 150%">)</span><span style="font-size: 12pt; line-height: 150%">”</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">看着ll一脸难色，dd进而道：“解决这个问题，就算你及格了</span> <span style="font-size: 12pt; line-height: 150%">”</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">ll</span> <span style="font-size: 12pt; line-height: 150%">：- -......</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; line-height: 150%"> </div></div>

# Input

<div class="content"><div style="margin: 0cm 0cm 0pt 29.9pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">有且仅有一行，包含一个整数f(t)</span></div></div>

# Output

<div class="content"><div style="margin: 0cm 0cm 0pt 29.9pt; line-height: 150%"><span style="font-size: 12pt; line-height: 150%">应有且仅有一行，包含一个整数f(t</span><span style="font-size: 12pt; line-height: 150%">’</span><span style="font-size: 12pt; line-height: 150%">)</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
20<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">24</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

