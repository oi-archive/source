# 题目描述


<div>
USACO/theme(译 by Maigo Akisame)
<hr/>
</div>
<p>
描述
</p>
<p>
我们用N(1 &lt;= N &lt;=5000)个音符的序列来表示一首乐曲，每个音符都是1..88范围内的整数，每个数表示钢琴上的一个键。很不幸这种表示旋律的方法忽略了音符的时值，但这项编程任务是关于音高的，与时值无关。
</p>
<p>
许多作曲家围绕一个重复出现的“主题”来构建乐曲。在我们的乐曲表示法中，“主题”是整个音符序列的一个子序列，它需要满足如下条件：
</p>
<ul>
<li>
长度至少为5个音符
</li>
<li>
在乐曲中重复出现(可能经过转调，见下)
</li>
<li>
重复出现的同一主题不能重叠
</li>
</ul>
“转调”的意思是主题序列中每个音符都被加上或减去了同一个整数值。
<p>
给定一段乐曲，计算其中最长主题的长度(即音符数)。
</p>
<p>
<span style="color:red;"><b>本题时限为1秒钟!</b></span> 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: theme</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file theme.in)</span> 
</h3>
<p>
输出文件的第一行包含整数N。下面的每一行(最后一行可能除外)包含20个整数，表示音符序列。最后一行可能少于20个音符。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT(file theme.out)</span> 
</h3>
<p>
输出文件应只含一个整数，即最长主题的长度。如果乐曲中没有主题，那么输出0。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file theme.in)</span> 
</h3>
<pre>30
25 27 30 34 39 45 52 60 69 79 69 60 52 45 39 34 30 26 22 18
82 78 74 70 66 67 64 60 65 80</pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file theme.out)</span> 
</h3>
<pre>5</pre>
(这个长度为5的主题是输入文件中第一行的最后5个音符和第二行开头5个音符)
<p>
 
</p>
