# 题目描述


USACO/cryptcow<b>(译 by Jeru)</b> 
<div>
<b></b> 
<div>
<b></b> 
<p>
<b>Cryptcowgraphy</b>解密牛语
</p>
<hr/>
</div>
</div>
<p>
<span>描述</span> 
</p>
<p>
农民Brown和John的牛们计划协同逃出它们各自的农场。它们设计了一种加密方法用来保护它们的通讯不被他人知道。
</p>
<p>
如果一头牛有信息要加密，比如&#34;International Olympiad in Informatics&#34;，它会随机地把C，O，W三个字母插到到信息中（其中C在O前面，O在W前面），然后它把C与O之间的文字和 O与W之间的文字的位置换过来。这里是两个例子：
</p>
<pre>International Olympiad in Informatics
-&gt; 
CnOIWternational Olympiad in Informatics
</pre>
<pre>International Olympiad in Informatics
-&gt; 
International Cin InformaticsOOlympiad W
</pre>
<p>
为了使解密更复杂，牛们会在一条消息里多次采用这个加密方法（把上次加密的结果再进行加密）。一天夜里，John的牛们收到了一条经过多次加密的信息。请你写一个程序判断它是不是这条信息经过加密（或没有加密）而得到的：
</p>
<p>
<br/>
</p>
<p>
Begin the Escape execution at the Break of Dawn
</p>
<p>
<br/>
</p>
<pre> <span>格式</span> 
<p>
<b>PROGRAM NAME</b>:cryptcow
</p>

<p>
<b>INPUT FORMAT</b>:
</p>

<p>
(file cryptcow.in)
</p>

<p>
一行,不超过75个字符的加密过的信息。
</p>

<p>
<b>OUTPUT FORMAT</b>:
</p>

<p>
(file cryptcow.out)
</p>

<p>
一行，两个整数. 如果能解密成上面那条逃跑的信息，第一个整数应当为1，否则为0；如果第一个数为1，则第二个数表示此信息被加密的次数，否则第二个数为0。
</p>

<p>
<span></span> 
</p>

<p>
<span>SAMPLE INPUT </span> 
</p>

<pre>Begin the EscCution at the BreOape execWak of Dawn <span></span></pre>
<pre><span>SAMPLE OUTPUT </span> 
<pre>1 1
</pre>
<!-- 
NewPP limit report
Preprocessor node count: 15/1000000
Post-expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
--><!-- Saved in parser cache with key newnocow:pcache:idhash:876-0!*!*!!zh-cn!*!* and timestamp 20120711063439 --></pre>
</pre>
