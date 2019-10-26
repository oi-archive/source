
# Description

<div class="content"><p><span style="font-size: medium"><span style="color: #200000; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">小强不像他的朋友阿米巴那样热爱化学；相反，小强最喜欢的事情是数数，特别有的时候喜欢数树。</span><span lang="EN-US" style="color: #200000; font-family: &#34;Times New Roman&#34;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体"><br/>
</span><span style="color: #200000; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">　　小强发现来自自然界的一类无根树很特别：它们的所有非叶子节点的度数都是一样的。小强管这种无根树叫做正则无根树。例如，</span><span lang="EN-US" style="color: #200000; font-family: &#34;Times New Roman&#34;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">14</span><span style="color: #200000; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">个点的度数限制为</span><span lang="EN-US" style="color: #200000; font-family: &#34;Times New Roman&#34;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">4</span><span style="color: #200000; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">的正则无根树有以下２种：</span></span></p>
<p><span style="font-size: medium"><span style="color: #200000; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"><img alt="" src="/source/bzoj/2569/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMi8xKDcpLmpwZw==.jpg"/></span></span></p>
<p></p>
<p></p>
<div style="background: white; text-indent: 24pt" align="left"><span style="font-size: 12pt; color: #200000">小强想数</span><span style="font-size: 12pt; color: #200000">N</span><span style="font-size: 12pt; color: #200000">个点的度数限制为</span><span style="font-size: 12pt; color: #200000">M</span><span style="font-size: 12pt; color: #200000">的正则无根树有多少种。在热爱化学的阿米巴的怂恿下，小强把</span><span style="font-size: 12pt; color: #200000">M</span><span style="font-size: 12pt; color: #200000">的范围限制在了</span><span style="font-size: 12pt; color: #200000">4</span><span style="font-size: 12pt; color: #200000">以下，至于这么做在化学、量子物理学和哲学上的理由，小强至今没有搞懂。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　现在，你要写程序来满足小强数树的愿望。</span></div>
<div style="background: white" align="left"></div></div>

# Input

<div class="content"><div style="background: white" align="left"><span style="font-size: 12pt; color: #200000">　　一行用短线（减号）连接的两个整数</span><span style="font-size: 12pt; color: #200000">N</span><span style="font-size: 12pt; color: #200000">和</span><span style="font-size: 12pt; color: #200000">M</span><span style="font-size: 12pt; color: #200000">。</span></div>
<div style="background: white" align="left"></div></div>

# Output

<div class="content"><div style="background: white" align="left"><span style="font-size: 12pt; color: #200000">　　一行，表示</span><span style="font-size: 12pt; color: #200000">N</span><span style="font-size: 12pt; color: #200000">个点的度数限制为</span><span style="font-size: 12pt; color: #200000">M</span><span style="font-size: 12pt; color: #200000">的正则无根树的个数。保证这个数不是</span><span style="font-size: 12pt; color: #200000">0</span><span style="font-size: 12pt; color: #200000">。</span></div>
<div style="background: white" align="left"></div></div>

# Sample Input

<div class="content"><span class="sampledata">14-4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
<br/>
　　对于所有的测试点，1&lt;=N，1&lt;=M，保证答案不是0。<br/>
　　对于第1个测试点，M=1<br/>
　　对于第2个测试点，M=2<br/>
　　对于第3~5个测试点，M=3，N&lt;=202，其中，对于第3、4个测试点，N&lt;=22<br/>
　　对于第6~9个测试点，M=4，N&lt;=902，其中，对于第6个测试点，N&lt;=32<br/>
　　对于第10个测试点，N=6002，M=4。<br/>
　　一共10个测试点<br/>
 <br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day4 版权所有者：范浩强">2012国家集训队Round 1 day4 版权所有者：范浩强</a></p></div>

