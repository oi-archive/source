
# Description

<div class="content"><div>Recently, the cows have been competing with strings of balanced </div>
<div>parentheses and comparing them with each other to see who has the </div>
<div>best one. </div>
<div>Such strings are scored as follows (all strings are balanced): the </div>
<div>string &#34;()&#34; has score 1; if &#34;A&#34; has score s(A) then &#34;(A)&#34; has score </div>
<div>2*s(A); and if &#34;A&#34; and &#34;B&#34; have scores s(A) and s(B), respectively, </div>
<div>then &#34;AB&#34; has score s(A)+s(B). For example, s(&#34;(())()&#34;) = </div>
<div>s(&#34;(())&#34;)+s(&#34;()&#34;) = 2*s(&#34;()&#34;)+1 = 2*1+1 = 3. </div>
<div>Bessie wants to beat all of her fellow cows, so she needs to calculate </div>
<div>the score of some strings. Given a string of balanced parentheses </div>
<div>of length N (2 &lt;= N &lt;= 100,000), help Bessie compute its score. </div>
<div></div>
<div>计算“平衡字符串”的分数，“平衡字符串”是指由相同数量的‘（’和‘）’组成， </div>
<div>且以‘（’开头，以‘）’结尾的字符串。 </div>
<div>计算规则： </div>
<div>字符串“（）”的得分是1. </div>
<div>如果，平衡字符串“A”的得分是是S(A)，那么字符串“（A）”得分是2*S(A) ； </div>
<div>如果，“A”，“B” 得分分别是S(A)和S(B)，那么平衡字符串“AB”得分为S(A)+S(B) </div>
<div>例如：s(&#34;(())()&#34;) =s(&#34;(())&#34;)+s(&#34;()&#34;) = 2*s(&#34;()&#34;)+1 = 2*1+1 = 3.</div></div>

# Input

<div class="content"><p><font size="3" face="Times New Roman">* Line 1: A single integer: N <br/>
* Lines 2..N + 1: Line i+1 will contain 1 integer: 0 if the ith <br/>
character of the string is &#39;(&#39;, and 1 if the ith character of the string is &#39;)&#39; <br/>
第1行：N，平衡字符串长度 <br/>
第2至N+1行：Linei+1 整数0或1,0代表字符‘（’，1代表‘）’</font></p></div>

# Output

<div class="content"><p><font size="3" face="Times New Roman">* Line 1: The score of the string. Since this number can get quite large, output the score modulo 12345678910. <br/>
计算字符串得分，结果对12345678910取模</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
0<br/>
0<br/>
1<br/>
1<br/>
0<br/>
1<br/>
INPUT DETAILS:<br/>
This corresponds to the string &#34;(())()&#34;.</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

