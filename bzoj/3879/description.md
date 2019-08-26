
# Description

<div class="content"><p class="MsoNormal"><span lang="EN-US">(</span><span style="font-family:宋体;
mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">我并不想告诉你题目名字是什么鬼</span><span lang="EN-US">)</span></p>
<p class="MsoNormal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">有一个长度为</span><span lang="EN-US">n</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">的仅包含小写字母的字符串</span><span lang="EN-US">S,</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">下标范围为</span><span lang="EN-US">[1,n].</span></p>
<p class="MsoNormal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">现在有若干组询问</span><span lang="EN-US">,</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">对于每一个询问</span><span lang="EN-US">,</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">我们给出若干个后缀</span><span lang="EN-US">(</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">以其在</span><span lang="EN-US">S</span><span style="font-family:
宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">中出现的起始位置来表示</span><span lang="EN-US">),</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">求这些后缀两两之间的</span><span lang="EN-US">LCP(LongestCommonPrefix)</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">的长度之和</span><span lang="EN-US">.</span><span style="font-family:
宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">一对后缀之间的</span><span lang="EN-US">LCP</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">长度仅统计一遍</span><span lang="EN-US">.</span></p>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal"><span style="font-family: 宋体;">第一行两个正整数</span><span lang="EN-US">n,m,</span><span style="font-family: 宋体;">分别表示</span><span lang="EN-US">S</span><span style="font-family: 宋体;">的长度以及询问的次数</span><span lang="EN-US">.</span></p>
<p class="MsoNormal"><span style="font-family: 宋体;">接下来一行有一个字符串</span><span lang="EN-US">S.</span></p>
<p class="MsoNormal"><span style="font-family: 宋体;">接下来有</span><span lang="EN-US">m</span><span style="font-family: 宋体;">组询问</span><span lang="EN-US">,</span><span style="font-family: 宋体;">对于每一组询问</span><span lang="EN-US">,</span><span style="font-family: 宋体;">均按照以下格式在一行内给出</span><span lang="EN-US">:</span></p>
<p class="MsoNormal"><span style="font-family: 宋体;">首先是一个整数</span><span lang="EN-US">t,</span><span style="font-family: 宋体;">表示共有多少个后缀</span><span lang="EN-US">.</span><span style="font-family: 宋体;">接下来</span><span lang="EN-US">t</span><span style="font-family: 宋体;">个整数分别表示</span><span lang="EN-US">t</span><span style="font-family: 宋体;">个后缀在字符串</span><span lang="EN-US">S</span><span style="font-family: 宋体;">中的出现位置</span><span lang="EN-US">.</span></p>
<p class="MsoNormal"></p>
<p></p></div>

# Output

<div class="content"><div><span style="font-family: 宋体;">对于每一组询问</span><span lang="EN-US">,</span><span style="font-family: 宋体;">输出一行一个整数</span><span lang="EN-US">,</span><span style="font-family: 宋体;">表示该组询问的答案</span><span lang="EN-US">.</span><span style="font-family: 宋体;">由于答案可能很大</span><span lang="EN-US">,</span><span style="font-family: 宋体;">仅需要输出这个答案对于</span><span lang="EN-US">23333333333333333(</span><span style="font-family: 宋体;">一个巨大的质数</span><span lang="EN-US">)</span><span style="font-family: 宋体;">取模的余数</span><span lang="EN-US">.</span></div>
<div>
<p class="MsoNormal"></p>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
<br/>
popoqqq<br/>
<br/>
1 4<br/>
<br/>
2 3 5<br/>
<br/>
4 1 2 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
0<br/>
<br/>
0<br/>
<br/>
2<br/>
<br/>
Hint<br/>
<br/>
样例解释:<br/>
<br/>
对于询问一,只有一个后缀”oqqq”,因此答案为0.<br/>
<br/>
对于询问二,有两个后缀”poqqq”以及”qqq”,两个后缀之间的LCP为0,因此答案为0.<br/>
<br/>
对于询问三,有四个后缀”popoqqq”,”opoqqq”,”qqq”,”qq”,其中只有”qqq”,”qq”两个后缀之间的LCP不为0,且长度为2,因此答案为2.<br/>
<br/>
对于100%的测试数据,有S&lt;=5*10^5,且Σt&lt;=3*10^6.<br/>
<br/>
特别注意:由于另一世界线的某些参数发生了变化,对于一组询问,即使一个后缀出现了多次,也仅算一次.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By YGY">By YGY</a></p></div>

