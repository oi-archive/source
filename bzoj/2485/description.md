
# Description

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman"><span id="1319334815942S" style="display: none"> </span><span id="1319334725885S" style="display: none"> </span>
</font></span></p><p><font face="Times New Roman"><font face="Times New Roman">Evolution is a seemingly random process which works in a way which resembles certain approaches we use to get approximate solutions to hard combinatorial problems. You are now to do something completely different. <br/>
<br/>
Given a DNA string S from the alphabet {A,C,G,T}, find the minimal number of copy operations needed to create another string T. You may reverse the strings you copy, and copy both from S and the pieces of your partial T. You may put these pieces together at any time. You may only copy contiguous parts of your partial T, and all copied strings must be used in your final T. Example: From S = “ACTG” create T = “GTACTATTATA” <br/>
<br/>
Get GT......... by copying and reversing &#34;TG&#34; from S. <br/>
Get GTAC....... by copying &#34;AC&#34; from S. <br/>
Get GTAC...TA.. by copying &#34;TA&#34; from the partial T. <br/>
Get GTAC...TAAT by copying and reversing &#34;TA&#34; from the partial T. <br/>
Get GTACAATTAAT by copying &#34;AAT&#34; from the partial T. <br/>
<br/>
<br/>
<br/>
给你两个字符串S和T，要求你用尽量少的步数从S构造出T。每一步你可以做以下操作：从S或者T的片段中拷贝一个字符串，然后可以将这个字符串反向，然后你得到一个片段。片段可以随时合并，但不能拆分，并且所有的片段都要使用。从T中拷贝字符串只能从一个片段中拷贝。求你最少需要的步数。两个串的字符数≤18。 <br/>
</font></font></p><font face="Times New Roman">
</font><p></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">The first line of input gives a single integer, 1 ≤ t ≤ 100, the number of test cases. Then follow, for each test case, a line with the string S of length 1 ≤ m ≤ 18, and a line with the string T of length 1 ≤ n ≤ 18. <br/>
<br/>
</font></span></p>
<p></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">Output for each test case the number of copy operations needed to create T from S, or &#34;impossible&#34; if it cannot be done. <br/>
<br/>
</font></span></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p><span id="1319334726112E" style="display: none"> </span></p>
<p></p>
<p><span id="1319334815310E" style="display: none"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
ACGT<br/>
GTAC<br/>
A<br/>
C<br/>
ACGT<br/>
TGCA<br/>
ACGT<br/>
TCGATCGA<br/>
A<br/>
AAAAAAAAAAAAAAAAAA<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
impossible<br/>
1<br/>
4<br/>
6<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

