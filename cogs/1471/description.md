# 题目描述


<h3>
【题目描述】
</h3>
<p class="MsoNormal" style="text-indent:28.0pt;">
<span style="font-size:14.0pt;font-family:宋体;"> </span> 
</p>
<p class="MsoNormal" style="text-indent:21.0pt;">
<span style="font-family:宋体;">一个国际科研小组昨天发现了一张奇奇怪怪的纸片。他们相信它大约有一百万年的历史。而且，它包含了一些用外星语言写下的文本。下面是对于这种外星语言的所有已知事实：</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoListParagraph" style="margin-left:49.0pt;text-indent:-21.0pt;">
<span style="font-family:&#34;">1.<span style="font-size:7pt;font-family:&#39;Times New Roman&#39;;">         </span></span><span style="font-family:宋体;">外星语言的字母表由</span><span style="font-family:&#34;">P</span><span style="font-family:宋体;">个元音和</span><span style="font-family:&#34;">Q</span><span style="font-family:宋体;">个辅音构成。</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoListParagraph" style="margin-left:49.0pt;text-indent:-21.0pt;">
<span style="font-family:&#34;">2.<span style="font-size:7pt;font-family:&#39;Times New Roman&#39;;">         </span></span><span style="font-family:宋体;">外星语言的每个单词包含了至多</span><span style="font-family:&#34;">N</span><span style="font-family:宋体;">个元音和至多</span><span style="font-family:&#34;">N</span><span style="font-family:宋体;">个辅音。</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoListParagraph" style="margin-left:49.0pt;text-indent:-21.0pt;">
<span style="font-family:&#34;">3.<span style="font-size:7pt;font-family:&#39;Times New Roman&#39;;">         </span></span><span style="font-family:宋体;">在单词中元音总是在辅音之前，即每个单词由一段辅音和后面紧跟着的一段元音构成。</span><span style="font-family:&#34;"><br/>
</span><span style="font-family:宋体;">元音或辅音的个数都可以是零。</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoListParagraph" style="margin-left:49.0pt;text-indent:-21.0pt;">
<span style="font-family:&#34;">4.<span style="font-size:7pt;font-family:&#39;Times New Roman&#39;;">         </span></span><span style="font-family:宋体;">每个单词至少包含一个字母。</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoListParagraph" style="margin-left:49.0pt;text-indent:-21.0pt;">
<span style="font-family:&#34;">5.<span style="font-size:7pt;font-family:&#39;Times New Roman&#39;;">         </span></span><span style="font-family:宋体;">每个单词都可以有重音。外星人将重音标记在字母而非音节上。有三种可能的情况：单词没有重音，单词由一个重音（它可以在任一个字母上），单词有两个重音（一个在元音字母上，一个在辅音字母上）。</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoListParagraph" style="margin-left:49.0pt;text-indent:-21.0pt;">
<span style="font-family:&#34;">6.<span style="font-size:7pt;font-family:&#39;Times New Roman&#39;;">         </span></span><span style="font-family:宋体;">两个字母拼写完全相同，但重音不同的单词是不同的。</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-family:宋体;">科学家们希望知道外星语言中单词的总数。他们把这个任务作为练习留给了你。</span><span style="font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-family:宋体;">你的程序被要求返回外星语言中单词的总数模</span><span style="font-family:&#34;">M</span><span style="font-family:宋体;">的值。</span> 
</p>
<h3>
【输入格式】
</h3>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-family:宋体;">一行，有四个整数：</span><span style="font-family:&#34;">P</span><span style="font-family:宋体;">，</span><span style="font-family:&#34;">Q</span><span style="font-family:宋体;">，</span><span style="font-family:&#34;">N</span><span style="font-family:宋体;">，</span><span style="font-family:&#34;">M</span> 
</p>
<h3>
【输出格式】
</h3>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-family:宋体;">一行，一个整数：外星语言的单词总数模</span><span style="font-family:&#34;">M</span><span style="font-family:宋体;">的值</span> 
</p>
<h3>
【样例输入】
</h3>
<pre>sample1:
1 1 1 9

sample2:
2 3 2 1000

sample3:
1 1 1000000000 1000000000

sample4:
123 456 789 987654321</pre>
<h3>
【样例输出】
</h3>
<pre>sample1:
8

sample2:
577

sample3:
0

sample4:
345494202</pre>
<h3>
【提示】
</h3>
<p>
1&lt;=N,P,Q&lt;=10^9<br/>
1&lt;=M&lt;=10^9
</p>
<h3>
【来源】
</h3>
<p>
TopCoder Algorithm SRM 377, Div 1, 1000
</p>
