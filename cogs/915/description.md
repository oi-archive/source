# 题目描述


<div>
USACO/hidden(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
有时候程序员有很奇怪的方法来隐藏他们的口令。Billy&#34;Hacker&#34;Geits会选择一个字符串S（由L个小写字母组成，5&lt;=L&lt;=100,000），然后他把S顺时针绕成一个圈，每次取一个做开头字母并顺时针依次取字母而组成一个字符串。这样将得到一些字符串，他把它们排序后取出第一个字符串。把这个字符串的第一个字母在原字符串中的位置-1做为口令。
<p>
如字符串alabala，按操作的到7个字符串，排序后得：
</p>
<p>
aalabal<br/>
abalaal<br/>
alaalab<br/>
alabala<br/>
balaala<br/>
laalaba<br/>
labalaa
</p>
<p>
第一个字符串为aalabal，这个a在原字符串位置为7，7-1=6，则6为口令。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: hidden</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT</span> 
</h3>
<p>
第一行：一个数：L
</p>
<p>
第二行：字符串：S（每72个字符一个换行符）
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file hidden.in)</span> 
</h3>
<pre><span style="font-size:small;">7
alabala</span></pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT</span> 
</h3>
一行，为得到的口令<br/>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file hidden.out)</span> 
</h3>
<pre><span style="font-size:small;">6 </span></pre>
<p>
 
</p>
