# 题目描述


<p>
在进行文法分析的时候，通常需要检测一个单词是否在我们的单词列表里。为了提高查找和定位的速度，通常都要画出与单词列表所对应的单词查找树，其特点如下：
</p>
<ul>
<li>
根节点不包含字母，除根节点外每一个节点都仅包含一个大写英文字母；
</li>
<li>
从根节点到某一节点，路径上经过的字母依次连起来所构成的字母序列，称为该节点对应的单词。单词列表中的每个词，都是该单词查找树某个节点所对应的单词；
</li>
<li>
在满足上述条件下，该单词查找树的节点数最少。
</li>
</ul>
<p>
单词列表对应的单词查找树
</p>
<pre>A
AN
ASP
AS
ASC
ASCII
BAS
BASIC <a href="../../wiki/Image:Trie.gif"><img alt="Image:Trie.gif" src="../../mw/images/3/3e/Trie.gif" width="258" height="370" border="0"/></a> </pre>
<p>
对一个确定的单词列表，请统计对应的单词查找树的节点数（包括根节点）
</p>
<p>
[输入文件]
</p>
<p>
该文件为一个单词列表，每一行仅包含一个单词和一个换行/回车符。每个单词仅由大写的英文字符组成，长度不超过63个字符。文件总长度不超过32K，至少有一行数据。
</p>
<p>
[输出文件]
</p>
<p>
该文件中仅包含一个整数和一个换行/回车符。该整数为单词列表对应的单词查找树的节点数。
</p>
<p>
[输入输出文件样例]
</p>
<p>
Input
</p>
<pre>A
AN
ASP
AS
ASC
ASCII
BAS
BASIC
</pre>
<p>
Output
</p>
<pre>13
</pre>