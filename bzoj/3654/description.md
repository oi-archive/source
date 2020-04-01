
# Description

<div class="content"><p><span style="font-size: medium">有句老话说得好，人应该要成熟老练，也就是说不能 too simple，也不能 too young。但另外还有这么句老话，人无论何时都应该保持单纯而年轻的心态，换句话说，应该stay simple，stay young。<br/>
于是人们就疑惑了，到底应不应该听长者的话呢？不过，不管听还是不听，这与本题都没有任何关系。<br/>
长者有一个字符串集合S，此处集合的概念与数学中的集合不同，其中可以含有重复的元素。初始时 S 包含 n 个字符串 s1;s2;:::;sn。有下面两种操作：<br/>
• 向S 中加入一个已经存在于 S 中的字符串。<br/>
• 从S 中选出两个字符串，将这两个字符串拼接得到的字符串加入集合 S。<br/>
长者想要知道，进行任意多次操作之后，在S 中的所有字符串中，最长的回文子串可以有多长？长者毕竟身经百战，他发现长度可以是无穷大，这时你需要输出Infinity。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行含有一个整数 n，代表初始时集合的大小。<br/>
接下来的n行，每行含有一个字符串。第i行的字符串为si。保证字符串中只含有小写英文字母。<br/>
</span></p>
<p></p></div>

# Output

<div class="content"><p><font size="4">如果最长的回文子串的长度不为无穷大，则输出一个整数，代表其长度；否则输出Infinity。</font></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
abc<br/>
abacde<br/>
ecab<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">第一个样例中，将ecab与abacde拼接，得到e<strong>cababac</strong>de，其中加粗的部分就是最长的回文子串，长度为 7。可以证明不存在更长的回文子串。第二个样例中，可以将任意多个ha拼接起来，从而得到ha、haha、hahaha等任意奇数长度的回文子串。因此答案为无穷大，输出Infinity。</span></p><br/>
<p><span style="font-size: medium">N&lt;=100<br/><br/>
L&lt;=1000<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

