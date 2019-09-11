# 题目描述


<p>
【问题描述】
</p>
<p>
在有道搜索框中，当输入一个或者多个字符时，搜索框会出现一定数量的提示，如下图所示：
</p>
<p align="center">
<img src="/upload/image/20121103/20121103180026_71605.jpg" alt=""/> 
</p>
<p>
现在给你 N 个单词和一些查询，请输出提示结果，为了简这个问题，只需要输出以查询词为前缀的并且按字典序排列的最前面的 8 个单词，如果符合要求的单词一个也没有请只输出当前查询词。
</p>
<p>
【输入文件】
</p>
<p>
第一行是一个正整数 N ，表示词表中有 N 个单词。 <br/>
接下来有 N 行，每行都有一个单词，注意词表中的单词可能有重复，请忽略掉重复单词。所有的单词都由小写字母组成。 <br/>
接下来的一行有一个正整数 Q ，表示接下来有 Q 个查询。 <br/>
接下来 Q 行，每行有一个单词，表示一个查询词，所有的查询词也都是由小写字母组成，并且所有的单词以及查询的长度都不超过 20 ，且都不为空 <br/>
其中： N&lt;=10000,Q&lt;=10000
</p>
<p>
【输出文件】
</p>
<p>
对于每个查询，输出一行，按顺序输出该查询词的提示结果，用空格隔开。
</p>
<p>
【样例输入】 <br/>
youdao.in
</p>
<p>
10 <br/>
a <br/>
ab <br/>
hello <br/>
that <br/>
those <br/>
dict <br/>
youdao <br/>
world <br/>
your <br/>
dictionary <br/>
6 <br/>
bob <br/>
d <br/>
dict <br/>
dicti <br/>
yo <br/>
z <br/>
<br/>
【样例输出】
</p>
<p>
youdao.out
</p>
<p>
bob <br/>
dict dictionary <br/>
dict dictionary <br/>
dictionary <br/>
youdao your <br/>
z
</p>
