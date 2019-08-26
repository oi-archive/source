
# Description

<div class="content"><div>Farmer John&#39;s farm is in the shape of an N×N grid of fields (1≤N≤500), each labeled with a letter in the alphabet. For example:</div>
<div>ABCD</div>
<div>BXZX</div>
<div>CDXB</div>
<div>WCBA</div>
<div>Each day, Bessie the cow walks from the upper-left field to the lower-right field, each step taking her either one field to the right or one field downward. Bessie keeps track of the string that she generates during this process, built from the letters she walks across. She gets very disoriented, however, if this string is a palindrome (reading the same forward as backward), since she gets confused about which direction she had walked.</div>
<div></div>
<div>Please help Bessie determine the number of distinct routes she can take that correspond to palindromes. Different ways of obtaining the same palindrome count multiple times. Please print your answer modulo 1,000,000,007.</div>
<div>从n×n 的矩阵 左上角走到右下角会有一个长度 n+n+1的字符串，问有多少种走法使得路径字符串为回文？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N, and the remaining N lines contain the N rows of the grid of fields. Each row contains N characters that are in the range A..Z.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output the number of distinct palindromic routes Bessie can take, modulo 1,000,000,007.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
ABCD<br/>
BXZX<br/>
CDXB<br/>
WCBA</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
Bessie can make the following palindromes<br/>
1 x &#34;ABCDCBA&#34;<br/>
1 x &#34;ABCWCBA&#34;<br/>
6 x &#34;ABXZXBA&#34;<br/>
4 x &#34;ABXDXBA&#34;</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

