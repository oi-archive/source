# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
”你知道这次开会的内容吗？”，会场中，Mike问座位旁一脸严肃的Marvolo。
</p>
<p>
”据说是要举行一次投票”
</p>
<p>
”投票？中央要选举新一届领导核心了？”
</p>
<p>
”好像是的”，Marvolo一脸期待的说，”听说这次有一个强劲的候选人呢，好像叫Eric”
</p>
<p>
”你这么早就这样说，会不会给人一种钦定的感觉？”
</p>
<p>
”……”
</p>
<p>
<br/>
</p>
<p>
Marvolo提前知道了这一次开会的目的，是选举新任领导。但是因为参加会议的代表人数众多，选票难以统计。尽管如此还是阻挡不了代表们的好奇心。他们想知道被投票最多的人是谁，是谁第一个提出的。如果得票数最多的候选人不止一个，则输出最先被提出的得票最多的候选人及提出的代表。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入数据有若干行，规定格式是这样的：
</p>
<p>
前若干个小写字符表示代表的名字，后面是一个’:’（英文冒号）,后面的小写字符表示被提出的候选人的名字。
</p>
<p>
数据保证文件最后一行为一个”.”(不带引号)，作为文件的结束。该行数据不需要处理。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出文件共两行，第一行是一个小写的字符串，表示首先提出得票最多的候选人的那个代表的姓名。
</p>
<p>
第二行是一个字符串，表示得票最多的那个候选人的姓名。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
marvolo:godcowc
</p>

<p>
mike:oldwang
</p>

<p>
alice:bob
</p>

<p>
rapiz:godcowc
</p>

<p>
kz:menci
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
marvolo
</p>

<p>
godcowc
</p>
</pre>
<h3>
【数据范围】
</h3>
<p>
<br/>
</p>
<p>
题目保证所有输入数据的每一个字符串中只含有一个“:”，每个人的名字长度不超过10，并且输入数据行数不超过10^5。
</p>
<p>
对于30%的数据 n&lt;=10^3
</p>
<p>
对于50%的数据 n&lt;=10^4
</p>
<p>
对于100%的数据 n&lt;=10^5
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
Mike
</p>