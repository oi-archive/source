
# Description

<div class="content"><p><span style="font-size: medium"><br/>
Like all bovines, Farmer John&#39;s cows speak the peculiar &#39;Cow&#39;<br/>
language. Like so many languages, each word in this language comprises<br/>
a sequence of upper and lowercase letters (A-Z and a-z).  A word<br/>
is valid if and only if each ordered pair of adjacent letters in<br/>
the word is a valid pair.<br/>
<br/>
Farmer John, ever worried that his cows are plotting against him,<br/>
recently tried to eavesdrop on their conversation. He overheard one<br/>
word before the cows noticed his presence. The Cow language is<br/>
spoken so quickly, and its sounds are so strange, that all that<br/>
Farmer John was able to perceive was the total number of uppercase<br/>
letters, U (1 &lt;= U &lt;= 250) and the total number of lowercase<br/>
letters, L (1 &lt;= L &lt;= 250) in the word.<br/>
<br/>
Farmer John knows all P (1 &lt;= P &lt;= 200) valid ordered pairs of<br/>
adjacent letters.  He wishes to know how many different valid<br/>
words are consistent with his limited data.  However, since<br/>
this number may be very large, he only needs the value modulo<br/>
97654321.<br/>
<br/>
</span></p>
<div><span style="font-size: medium">   约翰的奶牛讲的是别人听不懂的“牛语”。牛语使用的字母就是英文字母，有大小写之分。牛语中存在P个合法的词素，每个词素都由两个字母组成。牛语的单词是由字母组成的序列，一个单词是有意义的充要条件是任意相邻的字母都是合法的词素。</span></div>
<div><span style="font-size: medium">    约翰担心他的奶牛正在密谋反对他，于是最近一直在偷听他们的对话。可是，牛语太复</span></div>
<div><span style="font-size: medium">杂了，他模模糊糊地只听到了一个单词，并确定了这个单词中有U个大写字母，L个小写字</span></div>
<div><span style="font-size: medium">母。现在他想知道，如果这个单词是有意义的，那么有多少种可能性呢？由于这个数字太大</span></div>
<div><span style="font-size: medium">了，你只要输出答案取97654321的余数就可以了。</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
* Line 1: Three space-separated integers: U, L and P<br/>
<br/>
* Lines 2..P+1: Two letters (each of which may be uppercase or<br/>
        lowercase), representing one valid ordered pair of adjacent<br/>
        letters in Cow.<br/>
<br/>
</span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">  </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行：三个用空格隔开的整数：</span><span lang="EN-US"><font face="Times New Roman">U</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">L</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">P</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US"><font face="Times New Roman">U</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．</span><span lang="EN-US"><font face="Times New Roman">L</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US"><font face="Times New Roman">250</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US"><font face="Times New Roman">P&lt;=</font></span><span lang="EN-US"><font face="Times New Roman">200</font></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">  </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第二行到</span><span lang="EN-US"><font face="Times New Roman">P+1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行：第</span><span lang="EN-US"><font face="Times New Roman">i+l</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">有两个字母，表示第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个词素，没有两个词素是完全相同的</span></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
* Line 1: A single integer, the number of valid words consistent with<br/>
        Farmer  John&#39;s data mod 97654321.<br/>
<span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">单个整数，表示符合条件的单词数量除以</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">97654321</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">的余数</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 7<br/>
AB<br/>
ab<br/>
BA<br/>
ba<br/>
Aa<br/>
Bb<br/>
bB<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The word Farmer John overheard had 2 uppercase and 2 lowercase<br/>
letters.  The valid pairs of adjacent letters are AB, ab, BA, ba,<br/>
Aa, Bb and bB.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">(</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">可能的单词为</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">AabB, Abba, abBA, BAab,BbBb, bBAa, bBbB)</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

