# 题目描述


<p align="left">
<strong>问题描述</strong> 
</p>
<p>
大家都知道，基因可以看作一个碱基对序列。它包含了 4 种核苷酸，简记作 A,C,G,T 。生物学家正致力于寻找人类基因的功能，以利用于诊断疾病和发明药物。
</p>
<p>
在一个人类基因工作组的任务中，生物学家研究的是：两个基因的相似程度。因为这个研究对疾病的治疗有着非同寻常的作用。两个基因的相似度的计算方法如下：
</p>
<p>
对于两个已知基因，例如 AGTGATG 和 GTTAG ，将它们的碱基互相对应。当然，中间可以加入一些空碱基 - ，例如：
</p>
<table cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td valign="top" width="19">
<p>
A
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
<td valign="top" width="19">
<p>
A
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
-
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
</tr>
<tr>
<td valign="top" width="19">
<p>
-
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
-
</p>
</td>
<td valign="top" width="19">
<p>
-
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
A
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
</tr>
</tbody>
</table>
<p>
<br/>
</p>
<p>
这样 , 两个基因之间的相似度就可以用碱基之间相似度的总和来描述，碱基之间的相似度如下表所示：
</p>
<p align="center">
<img src="/upload/image/20120925/20120925164154_98449.gif" alt=""/> 
</p>
<p>
那么相似度就是： (-3)+5+5+(-2)+(-3)+5+(-3)+5=9 。因为两个基因的对应方法不唯一，例如又有：
</p>
<table cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td valign="top" width="19">
<p>
A
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
<td valign="top" width="19">
<p>
A
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
</tr>
<tr>
<td valign="top" width="19">
<p>
-
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
T
</p>
</td>
<td valign="top" width="19">
<p>
A
</p>
</td>
<td valign="top" width="19">
<p>
-
</p>
</td>
<td valign="top" width="19">
<p>
G
</p>
</td>
</tr>
</tbody>
</table>
<p>
<br/>
</p>
<p>
相似度为： (-3)+5+5+(-2)+5+(-1)+5=14 。规定两个基因的相似度为所有对应方法中，相似度最大的那个。
</p>
<p>
<strong>输入 </strong> 
</p>
<p>
共两行。每行首先是一个整数，表示基因的长度；隔一个空格后是一个基因序列，序列中只含 A,C,G,T 四个字母。 1&lt;= 序列的长度 &lt;=100 。
</p>
<p>
<strong>输出 </strong> 
</p>
<p>
仅一行，即输入基因的相似度。
</p>
<p>
<strong>样例 </strong> 
</p>
<p>
gene.in
</p>
<p>
7 AGTGATG <br/>
5 GTTAG
</p>
<p>
gene.out
</p>
<p>
14
</p>
