<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>著名的考古学家石教授在云梦高原上发现了一处古代城市遗址。让教授欣喜的是在这个他称为冰峰城(Ice-Peak City)的城市中有12块巨大石碑，上面刻着用某种文字书写的资料，他称这种文字为冰峰文。然而当教授试图再次找到冰峰城时，却屡屡无功而返。</p>
<p>幸好当时教授把石碑上的文字都拍摄了下来，为了解开冰峰城的秘密，教授和他的助手牛博士开始研究冰峰文，发现冰峰文<strong><span style="text-decoration: underline;">只有陈述句这一种句型和名词(n)、动词(v)、辅词(a)这三类单词</span></strong>，且其文法很简单：</p>
<p>&lt;文章&gt;      ::= &lt;句子&gt; { &lt;句子&gt; }</p>
<p>&lt;句子&gt;      ::= &lt;陈述句&gt;</p>
<p>&lt;陈述句&gt;    ::= &lt;名词短语&gt; { &lt;动词短语&gt; &lt;名词短语&gt; } [ &lt;动词短语&gt; ]</p>
<p>&lt;名词短语&gt;  ::= &lt;名词&gt; | [ &lt;辅词&gt; ] &lt;名词短语&gt;</p>
<p>&lt;动词短语&gt;  ::= &lt;动词&gt; | [ &lt;辅词&gt; ] &lt;动词短语&gt;</p>
<p>&lt;单词&gt;      ::= &lt;名词&gt; | &lt;动词&gt; | &lt;辅词&gt;</p>
<p><strong>注：</strong>其中&lt;名词&gt;、&lt;动词&gt;和&lt;辅词&gt;由词典给出，“::=”表示<strong><span style="text-decoration: underline;">定义为</span></strong>，“|”表示<strong><span style="text-decoration: underline;">或</span></strong>，{}内的项可以<strong><span style="text-decoration: underline;">重复任意多次或不出现</span></strong>，[]内的项可以<strong><span style="text-decoration: underline;">出现一次或不出现</span></strong>。</p>
<p>在研究了大量资料后，他们总结了一部冰峰文词典，由于冰峰文恰好有26个字母，为了研究方便，用字母a到z表示它们。</p>
<p>冰峰文在句子和句子之间以及单词和单词之间没有任何分隔符，因此划分单词和句子令石教授和牛博士感到非常麻烦，于是他们想到了使用计算机来帮助解决这个问题。假设你接受了这份工作，你的第一个任务是写一个程序，将一篇冰峰文文章划分为最少的句子，在这个前提下，将文章划分为最少的单词。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>l  输入文件第1行为词典中的单词数n（n&lt;=1000）。</p>
<p>l  输入文件第2行至第(n+1)行每行表示一个单词，形为“<em>α.mot</em>”，<em> α</em>表示词性，可能是n(名词),v（动词）,a（辅词）中的一个，<em>mot</em>为单词，单词的长度不超过20。拼写相同而词性不同的单词视为不同的单词，如输入示例中的n.kick与v.kick是两个不同的单词。</p>
<p>l  输入文件第(n+2)行为需要划分的文章，以“.”结束。</p>
<p>l  输入文件中的文章确保为冰峰文。文章是由有限个句子组成的，每个句子只包含有限个单词。文章长度不超过5KB。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>l&nbsp; 输出文件为两行，每行一个整数。</p>
<p>l&nbsp; 输出文件第1行为划分出来的句子数。</p>
<p>l&nbsp; 输出文件第2行为划分出来的单词数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>11</p>
<p>n.table</p>
<p>n.baleine</p>
<p>a.silly</p>
<p>n.snoopy</p>
<p>n.sillysnoopy</p>
<p>v.is</p>
<p>v.isnot</p>
<p>n.kick</p>
<p>v.kick</p>
<p>a.big</p>
<p>v.cry</p>
<p>sillysnoopyisnotbigtablebaleinekicksnoopysillycry.</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>2</p>
<p>9</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（为了阅读方便，划分的单词用空格分隔，在单词的右上角标出它的词性，每行写一个句子，用句号表示句子结束。）</p>
<p>输出对应的划分：</p>
<p>sillysnoopy<sup>n</sup> isnot<sup>v</sup> big<sup>a</sup> table<sup>n</sup>.</p>
<p>baleine<sup>n</sup> kick<sup>v</sup> snoopy<sup>n</sup> silly<sup>a</sup> cry<sup>v</sup>.</p>
<p> </p>
<p>如果用下面的划分：</p>
<p>silly<sup>a</sup> snoopy<sup>n</sup> isnot<sup>v</sup> big<sup>a</sup> table<sup>n</sup>.</p>
<p>baleine<sup>n</sup> kick<sup>v</sup> snoopy<sup>n</sup> silly<sup>a</sup> cry<sup>v</sup>.</p>
<p>则划分的句子数仍为2个，但单词数却多了1个，为10个，显然应该按前者而不是后者划分。</p>
</div>
</div>