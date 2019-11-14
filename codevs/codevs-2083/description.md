<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农民Brown和John的牛们计划协同逃出它们各自的农场。它们设计了一种加密方法用来保护它们的通讯不被他人知道。</p>
<p>如果一头牛有信息要加密，比如"International Olympiad in Informatics"，它会随机地把C，O，W三个字母插到到信息中（其中C在O前面，O在W前面），然后它把C与O之间的文字和 O与W之间的文字的位置换过来。这里是两个例子：</p>
<pre>International Olympiad in Informatics
-&gt;
CnOIWternational Olympiad in Informatics
</pre>
<pre>International Olympiad in Informatics
-&gt;
International Cin InformaticsOOlympiad W
</pre>
<p>为了使解密更复杂，牛们会在一条消息里多次采用这个加密方法（把上次加密的结果再进行加密）。一天夜里，John的牛们收到了一条经过多次加密的信息。请你写一个程序判断它是不是这条信息经过加密（或没有加密）而得到的：</p>
<pre>Begin the Escape execution at the Break of Dawn</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一行,不超过75个字符的加密过的信息。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一行，两个整数. 如果能解密成上面那条逃跑的信息，第一个整数应当为1，否则为0；如果第一个数为1，则第二个数表示此信息被加密的次数，否则第二个数为0。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>Begin the EscCution at the BreOape execWak of Dawn</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>