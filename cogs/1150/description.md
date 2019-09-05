# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">编码工作常被运用于密文或压缩传输。这里我们用一种最简单的编码方式进行编码：把一些有规律的单词编成数宇。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">字母表中共有<span>26</span><span>个字母</span><span>{a</span><span>，</span><span>b</span><span>，…，</span><span>z}</span><span>，这些特殊的单词长度不超过</span><span>6</span><span>且字母按升序排列。把所有这样的单词放在一起，按字典顺序排列，一个单词的编码就对应着它在字典中的位置。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">例如：a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">→</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">→</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"> ...... z</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">→</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">26  ab</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">→</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">27</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> ac</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">→</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">28 ......</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">你的任务就是对于所给的单词，求出它的编码。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
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
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">仅一行，被编码的单词。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
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
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">仅一行，对应的编码。如果单词不在字母表中，输出<span>0</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>ab</pre>
<h3>
【样例输出】
</h3>
<pre>27</pre>
