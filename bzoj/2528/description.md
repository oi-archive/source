
# Description

<div class="content"><p></p>
<p></p>
<p></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">Byteasar, the king of Bitotia, has ordained a reform of his subjects&#39; names. The names of Bitotians often contain repeating phrases, e.g., the name </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">Abiabuabiab</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma"> has two occurrences of the phrase </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">abiab</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">. Byteasar intends to change the names of his subjects to sequences of bits matching the lengths of their original names. Also, he would very much like to reflect the original repetitions in the new names. </span></span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">In the following, for simplicity, we will identify the upper- and lower-case letters in the names. For any sequence of characters (letters or bits)W=W1W2...Wk we say that the integer P(1&lt;=P&lt;K) is a period of w if Wi=Wi+P for all i=1,...,k-p. We denote the set of all periods of w by Per(w). For example,Per(ABIABUABIAB={6,9}, Per(01001010010)={5,8,10}, andPer(0000)={1,2,3}. </span></span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">Byteasar has decided that every name is to be changed to a sequence of bits that: </span></span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 191.25pt; text-indent: -18pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Symbol">·<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">has length matching that of the original name, </span></span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 191.25pt; text-indent: -18pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Symbol">·<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">has the same set of periods as the original name, </span></span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 191.25pt; text-indent: -18pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Symbol">·<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">is the smallest (lexicographically<sup>1</sup>) sequence of bits satisfying the previous conditions. </span></span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">For example, the name </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">ABIABUABIAB</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma"> should be changed to </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">01001101001</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">, </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">BABBAB</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma"> to </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">010010</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">, and </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">BABURBAB</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma"> to </span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: 宋体">01000010</span><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">. </span></span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 140%"><span style="font-size: medium"><span lang="EN-US" style="color: rgb(68,68,68); line-height: 140%; font-family: Tahoma">Byteasar has asked you to write a program that would facilitate the translation of his subjects&#39; current names into new ones. If you succeed, you may keep your current name as a reward!</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 140%"><span style="font-size: medium">给定一个字符串S，其长度为N，如果对于任意的i(1&lt;=i&lt;=n-t)有Si=Si+t(1&lt;=t&lt;n-1)，那么称其满足性质g(T)。定义Per(S)为所有使得S满足性质g(T)的整数T的集合。</span></p>
<p></p>
<pre style="font-family: arial, verdana, helvetica, sans-serif! important"><span style="font-size: medium">例如：Per(ABIABUABIAB)={6,9}, Per(01001010010)={5,8,10}, Per(0000)={1,2,3}. 你的任务是构造一个长度恰好为N的01串，使得： 第一，该串的Per集合和S相等。 第二，在所有满足条件1的01串中，该串的字典序最小。  输入： 第一行是一个整数K，表示这个数据里你要处理K个问题。 接下来K行，每行有一个仅包含大写字母并且长度不超过200000的字符串。 输出： </span></pre>
<p></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"></p>
<p><span style="font-size: medium">
</span></p><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p>K行，第I行对应输入的第i个字符串的答案。如果不存在这样的01串，输出XXX。<br/>
</p>
<p></p>
<p></p></div>

# Input

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In the first line of the standard input there is a single integer k- the number of names to be translated (1&lt;=k&lt;=20). The names are given in the following lines, one in each line. Each name consists of no less than and no more than 200000upper-case (capital) letters (of the English alphabet). </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In the test worth 30% of the points each name consists of at most 20letters. </span></span></div></div>

# Output

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Your program should print lines to the standard output. Each successive line should hold a sequence of zeroes and ones (without spaces in between) corresponding to the names given on the input. If an appropriate sequence of bits does not exists for some names, then &#34;</span><span style="color: #444444; line-height: 140%">XXX</span><span style="color: #444444; line-height: 140%">&#34; (without quotation marks) should be printed for that name. </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
ABIABUABIAB<br/>
BABBAB<br/>
BABURBAB<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">01001101001<br/>
010010<br/>
01000010<br/>
<br/>
--------------------------------------------------------------------------------<br/>
<br/>
1 The sequence of bits I1I2...Ik is lexicographically smaller than the sequence of bits Y1Y2...Yk if for some i, 1&lt;=i&lt;=k, we have Ii<yi and="" for="" all="" j="1,...,i-1" we="" have="" ij="Yj." <="" span=""></yi></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 Object022">鸣谢 Object022</a></p></div>

