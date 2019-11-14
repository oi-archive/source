
# Description

<div class="content"><div align="left"><span style="font-size: 12pt">Fish</span><span style="font-size: 12pt">是一条生活在海里的鱼。有一天他很无聊，就到处去寻宝。他找到了位于海底深处的宫殿，但是一扇带有密码锁的大门却阻止了他的前进。通过翻阅古籍，Fish 得知了这个密码的相关信息：</span></div>
<div align="left"> </div>
<div align="left"><span style="font-size: 12pt">1. </span><span style="font-size: 12pt">该密码的长度为N。</span></div>
<div align="left"> </div>
<div align="left"><span style="font-size: 12pt">2. </span><span style="font-size: 12pt">密码仅含小写字母。</span></div>
<div align="left"> </div>
<div align="left"><span style="font-size: 12pt">3. </span><span style="font-size: 12pt">以每一个字符为中心的最长回文串长度。</span></div>
<div align="left"> </div>
<div align="left"><span style="font-size: 12pt">4. </span><span style="font-size: 12pt">以每两个相邻字符的间隙为中心的最长回文串长度。</span></div>
<div align="left"> </div>
<div align="left"><span style="font-size: 12pt">很快Fish 发现可能有无数种满足条件的密码。经过分析，他觉得这些密码中字典序最小的一个最有可能是答案，你能帮他找到这个密码么？</span></div>
<div align="left"><span style="font-size: 12pt">注意：对于两个串A和B，如果它们的前i个字符都相同，而A的第i+1个字符比B的第i+1个字符小，那么认为是则称密码A 的字典序小于密码B 的字典序，例如字符串abc 字典序小于字符串acb。如果密码A的字典序比其他所有满足条件的密码的字典序都小，则密码A是这些密码中字典序最小的一个。</span></div>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; mso-pagination: widow-orphan"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt">输入由三行组成。<span lang="EN-US"><br/>
</span>第一行仅含一个整数<span lang="EN-US">N</span>，表示密码的长度。<span lang="EN-US"><br/>
</span>第二行包含<span lang="EN-US">N </span>个整数，表示以每个字符为中心的最长回文串长度。<span lang="EN-US"><br/>
</span>第三行包含<span lang="EN-US">N - 1 </span>个整数，表示每两个相邻字符的间隙为中心的最长回文串长度。<span lang="EN-US"><br/>
<br/>
</span>对于<span lang="EN-US">20% </span>的数据，<span lang="EN-US">1 &lt;= n &lt;= 100</span>。<span lang="EN-US"><br/>
</span>另有<span lang="EN-US">30% </span>的数据，<span lang="EN-US">1 &lt;= n &lt;= 1000</span>。<span lang="EN-US"><br/>
</span>最后<span lang="EN-US">50% </span>的数据，<span lang="EN-US">1 &lt;= n &lt;= 10^5</span>。<span lang="EN-US"> <o:p></o:p></span></span></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; mso-pagination: widow-orphan"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt">输出仅一行。输出满足条件的最小字典序密码。古籍中的信息是一定正确的，故一定存在满足条件的密码。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; mso-pagination: widow-orphan"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample #1<br/>
3<br/>
1 1 1<br/>
0 0<br/>
<br/>
Sample #2<br/>
3<br/>
1 3 1<br/>
0 0<br/>
<br/>
Sample #3<br/>
3<br/>
1 3 1<br/>
2 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Sample #1<br/>
abc<br/>
<br/>
Sample #2<br/>
aba<br/>
<br/>
Sample #3<br/>
aaa<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="462" alt="" width="656" src="/source/bzoj/3325/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMi80NC5qcGc=.jpg"/></p><br/>
<p></p><br/>
<p></p><br/>
<p>应上传者要求，此系列试题不公开,如有异议，本站将删除之。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

