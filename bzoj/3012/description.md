
# Description

<div class="content"><p><span style="font-size: medium">Bessie has been playing with strings again. She found that by changing the order of the alphabet she could make some strings come before all the others lexicographically (dictionary ordering). For instance Bessie found that for the strings &#34;omm&#34;, &#34;moo&#34;, &#34;mom&#34;, and &#34;ommnom&#34; she could make &#34;mom&#34; appear first using the standard alphabet and that she could make &#34;omm&#34; appear first using the alphabet &#34;abcdefghijklonmpqrstuvwxyz&#34;. However, Bessie couldn&#39;t figure out any way to make &#34;moo&#34; or &#34;ommnom&#34; appear first. Help Bessie by computing which strings in the input could be lexicographically first by rearranging the order of the alphabet. To compute if string X is lexicographically before string Y find the index of the first character in which they differ, j. If no such index exists then X is lexicographically before Y if X is shorter than Y. Otherwise X is lexicographically before Y if X[j] occurs earlier in the alphabet than Y[j]. </span></p>
<div>给定n个总长不超过m的互不相同的字符串，现在你可以任意指定字符之间的大小关系。问有多少个串可能成为字典</div>
<div>序最小的串，并输出这些串。n &lt;= 30,000 , m &lt;= 300,000</div></div>

# Input

<div class="content"><p><font size="4">* Line 1: A single line containing N (1 &lt;= N &lt;= 30,000), the number of strings Bessie is playing with. </font></p>
<p><font size="4">* Lines 2..1+N: Each line contains a non-empty string. The total number of characters in all strings will be no more than 300,000. All characters in input will be lowercase characters &#39;a&#39; through &#39;z&#39;. Input will contain no duplicate strings.</font></p></div>

# Output

<div class="content"><p> * Line 1: A single line containing K, the number of strings that could be lexicographically first.</p>
<p> * Lines 2..1+K: The (1+i)th line should contain the ith string that could be lexicographically first. Strings should be output in the same order they were given in the input. </p></div>

# Sample Input

<div class="content"><span class="sampledata"> 4<br/>
omm <br/>
moo <br/>
mom <br/>
ommnom <br/>
INPUT DETAILS: The example from the problem statement. <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 2<br/>
omm <br/>
mom <br/>
<br/>
OUTPUT DETAILS: Only &#34;omm&#34; and &#34;mom&#34; can be ordered first.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

