# 题目描述


<div>
USACO/twofive(译 ioi)
<hr/>
</div>
<p>
描述
</p>
有一种奇怪的语言叫做“二五语言”。它的每个单词都由A～Y这25个字母各一个组成。但是，并不是任何一种排列都是一个合法的二五语言单词。二五语言的单词必须满足这样一个条件：把它的25个字母排成一个5*5的矩阵，它的每一行和每一列都必须是递增的。比如单词ACEPTBDHQUFJMRWGKNSXILOVY，它排成的矩阵如下所示：
<pre>A C E P T
B D H Q U
F J M R W
G K N S X
I L O V Y
</pre>
因为它的每行每列都是递增的，所以它是一个合法的单词。而单词YXWVUTSRQPONMLKJIHGFEDCBA则显然不合法。
<p>
由于单词太长存储不便，需要给每一个单词编一个码。编码方法如下：从左到右，再从上到下，可以由一个矩阵的得到一个单词，再把单词按照字典顺序排序。比如，单词ABCDEFGHIJKLMNOPQRSTUVWXY的编码为1，而单词ABCDEFGHIJKLMNOPQRSUTVWXY的编码为2。
</p>
<p>
现在，你需要编一个程序，完成单词与编码间的转换。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: twofive</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT</span> 
</h3>
<ul>
<li>
第一行为一个字母N或W。N表示把编码转换为单词，W表示把单词转换为编码。
</li>
<li>
若第一行为N，则第二行为一个整数，表示单词的编码。若第一行为W，则第二行为一个合法的单词。
</li>
</ul>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT  #1(file twofive.in)</span> 
</h3>
<pre>N
2</pre>
<pre><span style="font-family:&#39;Times New Roman&#39;;font-size:medium;"><b>SAMPLE INPUT #2</b></span></pre>
<pre>W </pre>
<pre>ABCDEFGHIJKLMNOPQRSUTVWXY
</pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT</span> 
</h3>
每行一个整数或单词。
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT #1(file twofive.out)</span> 
</h3>
<pre>ABCDEFGHIJKLMNOPQRSUTVWXY
</pre>
<pre><span style="font-family:&#39;Times New Roman&#39;;font-size:medium;"><b>SAMPLE OUTPUT #2</b></span></pre>
<pre>2<span style="font-size:small;"> </span></pre>
<p>
 
</p>
