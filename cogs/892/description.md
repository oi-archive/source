# 题目描述


<p>
<br/>
</p>
<p>
由于cogs的环境（无法打开两个输入文件），本题无法正常运行。
</p>
<p>
请前往题目：1431. 字母游戏（修复后）提交程序，注意输入输出格式要做相应变动
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
USACO/lgame(译by kd)
</p>
<hr/>
<p>
<br/>
</p>
<p>
描述
</p>
<h3 align="center">
<img alt="" src="/images/upload/image/20120711/20120711173100_35937.gif"/> 
</h3>
<p>
    在家里用电视机做字母游戏是很流行的，其中一种玩法是:每一个字母有一个数值与之对应.你收集字母组成一个或多个词以得到尽可能高的得分.除非你已有了 “找词的方法”(“a way with words”)，你会把你知道的字都试一遍.有时你也许会查阅其拼写，然后计算得分。显然可以用计算机更为准确地完成此任务。上图示出了英文字母及其所对应的值，当给出英文单词(word) 的表列及收集的字母时，请找出所能形成的得分最高的词或词对(pairs of words)。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: lgame</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file lgame.in)</span> 
</h3>
<p>
    输入文件lgame.in中有一行由小写字母(&#39;a&#39;到&#39;z&#39;)组成的字符串， 这就是收集到字母(就是可以使用的字母)，字符串由至少3个字母至多7个字母(以任意顺序) 组成。
</p>
<p>
    词典文件lgame.dict由至多40，000行组成，文件的最后一行有&#39;.&#39; 表示文件的结束。文件中的字已按字母顺序排序。其它各行每一行都是由至少3个小写字<span style="font-size:small;">母</span>，至多7 个小写字母组成的字符串。文件中的字已按字母顺序排序。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT(file lagame.out)</span> 
</h3>
<p>
在文件lgame.out的第一行，你的程序应写上最高得分(子任务A).使用上面图形中给出的字母-值对应表。
</p>
<p>
随后的每一行是由文件lgame.dict中查到的具有这个得分的所有的词和或词对(word pairs)(子任务B)。要利用图中给定的字母的值。
</p>
<p>
当两个词能够形成 一个组合(具有给定的字母)时，这两个词应该打印到同一行，两个词中间用一个空格隔开。不许重复表示词对，例如&#39;rag prom&#39;和&#39;prom rag&#39;是同样的词对，只输出字典顺序较小的那个（prom rag）。
</p>
<p>
输出要按照字典顺序排序，如果两个词对第一个单词的顺序相同，则按照第二个单词。一个词对中的两个单词可以相同。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file lgame.in)</span> 
</h3>
<pre><span style="font-size:small;">prmgroa </span></pre>
<pre><span style="font-family:&#39;Times New Roman&#39;;font-size:medium;"><b>SAMPLE INPUT (file lgame.dict)</b></span></pre>
<pre><span style="font-size:small;">profile
program
prom
rag
ram
rom
.</span> </pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file lagame.out)</span> 
</h3>
<pre><span style="font-size:small;">24
program
prom rag </span></pre>
<p>
 
</p>
