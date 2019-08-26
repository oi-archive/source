
# Description

<div class="content"><p class="NOI1" style="margin: 13pt 0cm"></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">XX</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在进行字符串研究的时候，遇到了一个十分棘手的问题。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在这个问题中，给定一个字符串</span><span lang="EN-US"><font face="Times New Roman">S</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，与一个整数</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，定义</span><span lang="EN-US"><font face="Times New Roman">S</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的子串</span><span lang="EN-US"><font face="Times New Roman">T=S(i, j)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">是关于第</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">位的识别子串，满足以下两个条件：</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; mso-list: l0 level1 lfo1"><font size="3"><font face="Times New Roman"><span lang="EN-US" style="mso-fareast-font-family: &#39;Times New Roman&#39;"><span style="mso-list: Ignore">1、</span></span><span lang="EN-US">i</span></font><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US"><font face="Times New Roman">j</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; mso-list: l0 level1 lfo1"><font size="3"><span lang="EN-US" style="mso-fareast-font-family: &#39;Times New Roman&#39;"><span style="mso-list: Ignore"><font face="Times New Roman">2、</font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">子串</span><span lang="EN-US"><font face="Times New Roman">T</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只在</span><span lang="EN-US"><font face="Times New Roman">S</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">中出现过一次。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; text-indent: 0cm; mso-char-indent-count: 0"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">例如，</span><span lang="EN-US"><font face="Times New Roman">S=&#34;banana&#34;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">K=5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，则关于第</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">位的识别子串有</span><span lang="EN-US"><font face="Times New Roman">&#34;nana&#34;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">&#34;anan&#34;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">&#34;anana&#34;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">&#34;nan&#34;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">&#34;banan&#34;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">&#34;banana&#34;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; text-indent: 0cm; mso-char-indent-count: 0"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">现在，给定</span><span lang="EN-US"><font face="Times New Roman">S</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">XX</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">希望知道对于</span><span lang="EN-US"><font face="Times New Roman">S</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的每一位，最短的识别子串长度是多少，请你来帮助他。</span></font></p>
<p></p></div>

# Input

<div class="content"><p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">仅一行，输入长度为</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的字符串</span><span lang="EN-US"><font face="Times New Roman">S</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.0pt"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行一个整数，第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行的整数表示对于第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">位的最短识别子串长度。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.0pt"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">agoodcookcooksgoodfood<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
1<br/>
<br/>
2<br/>
<br/>
3<br/>
<br/>
3<br/>
<br/>
2<br/>
<br/>
2<br/>
<br/>
3<br/>
<br/>
3<br/>
<br/>
2<br/>
<br/>
2<br/>
<br/>
3<br/>
<br/>
3<br/>
<br/>
2<br/>
<br/>
1<br/>
<br/>
2<br/>
<br/>
3<br/>
<br/>
3<br/>
<br/>
2<br/>
<br/>
1<br/>
<br/>
2<br/>
<br/>
3<br/>
<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=5*10^5</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

