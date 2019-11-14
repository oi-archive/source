
# Description

<div class="content"><p><span style="font-size: medium">YY is a clever boy. One day, he feels very boring and writes some expressions randomly. Later, he discovers that although some expressions were written in different forms, they are essentially the same, such as a+(b-c), (a+b)-c. After several attempts, he becomes interested in this and wants to know the number of distinct expressions involving n different operands. To make the problem easier, you can assume that only operators +, -, *, / and parentheses are permitted. </span></p>
<div><span style="font-size: medium">有一些表达式本质上是相同的，如a+(b-c), (a+b)-c。你的任务是统计出N元的不同表达式有多少个。</span></div>
<div><span style="font-size: medium">为使问题简单些，只有+-*/和括号是允许的。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">The input consists of multiple test cases. For each test case, there is one line containing only one integer n. (1&lt;=n&lt;=30) End of input is indicated by a line containing a zero. </span></p>
<div><span style="font-size: medium">一个整数N，意义如上描述。N&lt;=30。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">For each test case, output the number of distinct expressions involving n different operands. Since the answer is very large, you only need to output the answer modulo 1,000,000,007. </span></p>
<div><span style="font-size: medium">一个整数表示表达式个数。</span></div>
<div><span style="font-size: medium">因为答案可能很大，只需输出对1,000,000,007取模后的值。</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
4<br/>
0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
6<br/>
68<br/>
1170<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">There are 6 distinct expressions involving 2 operands: a+b, a-b, b-a, a*b, a/b, b/a. There are 68 distinct expressions involving 3 operands: a+b+c, a+b-c, a-b+c, a-b-c, b-a+c, b-a-c, c-a-b, a*b*c, a*b/c, a/b*c, a/b/c, b/a*c, b/a/c, c/a/b, a+b*c, b+a*c, c+a*b, a+b/c, a+c/b, b+a/c, b+c/a, c+a/b, c+b/a, a-b*c, b-a*c, c-a*b, a-b/c, a-c/b, b-a/c, b-c/a, c-a/b, c-b/a, b*c-a, a*c-b, a*b-c, b/c-a, c/b-a, a/c-b, c/a-b, a/b-c, b/a-c, a*(b+c), b*(a+c), c*(a+b), a*(b-c), a*(c-b), b*(a-c), b*(c-a), c*(a-b), c*(b-a), a/(b+c), b/(a+c), c/(a+b), a/(b-c), a/(c-b), b/(a-c), b/(c-a), c/(a-b), c/(b-a), (b+c)/a, (a+c)/b, (a+b)/c, (b-c)/a, (c-b)/a, (a-c)/b, (c-a)/b, (a-b)/c, (b-a)/c. When n=4, note that (a-b)/(c-d) and (b-a)/(d-c) are the same, but a/b-c/d and b/a-d/c are not. </span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><b><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">提示：</span></b></span><b><font size="3"><span lang="EN-US"><o:p></o:p></span></font></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">二元的表达式：</span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a+b, a-b, b-a, a*b, a/b, b/a. </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">三元的表达式：</span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a+b+c, a+b-c, a-b+c, a-b-c, b-a+c, b-a-c, c-a-b, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a*b*c, a*b/c, a/b*c, a/b/c, b/a*c, b/a/c, c/a/b, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a+b*c, b+a*c, c+a*b, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a+b/c, a+c/b, b+a/c, b+c/a, c+a/b, c+b/a, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a-b*c, b-a*c, c-a*b, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a-b/c, a-c/b, b-a/c, b-c/a, c-a/b, c-b/a, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">b*c-a, a*c-b, a*b-c, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">b/c-a, c/b-a, a/c-b, c/a-b, a/b-c, b/a-c, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a*(b+c), b*(a+c), c*(a+b), </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a*(b-c), a*(c-b), b*(a-c), b*(c-a), c*(a-b), c*(b-a), </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a/(b+c), b/(a+c), c/(a+b), </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">a/(b-c), a/(c-b), b/(a-c), b/(c-a), c/(a-b), c/(b-a), </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">(b+c)/a, (a+c)/b, (a+b)/c, </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">(b-c)/a, (c-b)/a, (a-c)/b, (c-a)/b, (a-b)/c, (b-a)/c. </font></span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">注意四元的表达式中</span><span lang="EN-US"><font face="Times New Roman">(a-b)/(c-d)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">(b-a)/(d-c)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">是相同的，而</span><span lang="EN-US"><font face="Times New Roman">a/b-c/d</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">b/a-d/c</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">是不同的。</span></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

