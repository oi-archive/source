
# Description

<div class="content"><p><span style="font-size: medium"> Farmer John has secret message that he wants to hide from his cows; the message is a string of length at least 2 containing only the characters A..Z. To encrypt his message, FJ applies a sequence of &#34;operations&#34; to it, where an operation applied to a string S first shortens S by removing either some (but not all) of the initial characters or some (but not all) of the final characters from S, after which the original string S is attached either at the beginning or end. For example, a single operation to the string ABC could result in eight possible strings: AABC ABABC BCABC CABC ABCA ABCAB ABCBC ABCC Given the final encrypted string, please count the number of possible ways FJ could have produced this string using one or more repeated operations applied to some source string. Operations are treated as being distinct even if they give the same encryption of FJ&#39;s message. For example, there are four distinct separate ways to obtain AAA from AA. Print your answer out modulo 2014.</span></p>
<p></p>
<div>XYW和他的男人聊天的时候，不让DZY看见他们聊天内容，他们决定用以下方式给一个字符串加密：每次把这个字符串的一个非空前缀或者后缀（不能是这个字符串的本身）加到这个字符串的前面或者后面。比如ABC就可以加密成 AABC ABABC BCABC CABC ABCA ABCAB ABCBC ABCC。</div>
<div>现在DZY拿到一个字符串（长度至多100），已知这个字符串从一个长度最少为2的字符串经过了至少一次加密（可以多次），现在DZY想要知道有多少种加密方案可以加密得到当前的字符串（初始字符串不同或者操作序列不同都视为不同的方案，结合样例解释食用更佳）。请你输出方案数对2014取模的值。</div></div>

# Input

<div class="content"><p><font size="4">* Line 1: A single encrypted string of length at most 100. </font></p></div>

# Output

<div class="content"><p><span style="font-size: medium"> * Line 1: The number of ways FJ could have produced this string with one or more successive operations applied to some initial string of length at least 2, written out modulo 2014. If there are no such ways, output zero. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">ABABA <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 8 <br/>
OUTPUT DETAILS: Here are the different ways FJ could have produced ABABA:<br/>
1. Start with ABA -&gt; AB+ABA<br/>
2. Start with ABA -&gt; ABA+BA <br/>
3. Start with AB -&gt; AB+A -&gt; AB+ABA<br/>
4. Start with AB -&gt; AB+A -&gt; ABA+BA <br/>
5. Start with BA -&gt; A+BA -&gt; AB+ABA <br/>
6. Start with BA -&gt; A+BA -&gt; ABA+BA <br/>
7. Start with ABAB -&gt; ABAB+A<br/>
8. Start with BABA -&gt; A+BABA </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

