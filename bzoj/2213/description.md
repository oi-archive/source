
# Description

<div class="content"><p>A word consisting of lower-case letters of the English alphabet (&#39;a&#39;-&#39;z&#39;) is given. We would like to choose a non-empty contiguous (i.e. one-piece) fragment of the word so as to maximise the difference in the number of occurrences of the most and the least frequent letter in the fragment. We are assuming that the least frequent letter has to occur at least once in the resulting fragment. In particular, should the fragment contain occurrences of only one letter, then the most and the least frequent letter in it coincide.</p>
<p>已知一个长度为n的由小写字母组成的字符串，求其中连续的一段，满足该段中出现最多的字母出现的个数减去该段中出现最少的字母出现的个数最大。求这个个数。</p>
<p></p></div>

# Input

<div class="content"><p>The first line of the standard input holds one integer (1&lt;=N&lt;=1000000)() that denotes the length of the word. The second line holds a word consisting of lower-case letters of the English alphabet.</p>
<p>第一行，n<br/>
第二行，该字符串<br/>
1&lt;=n&lt;=1000000</p>
<p></p></div>

# Output

<div class="content"><p>The first and only line of the standard output is to hold a single integer, equal to the maximum difference in the number of occurrences of the most and the least frequent letter that is attained in some non-empty contiguous fragment of the input word.</p>
<p>一行，表示结果</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
aabbaaabab<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
Explanation of the example: The fragment that attains the difference of 3 in the number of occurrences of a and b is aaaba. <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

