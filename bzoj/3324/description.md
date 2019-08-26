
# Description

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">Fish</span><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">是一条生活在海里的鱼，有一天他很无聊，于是他去捡了人类扔进海里的垃圾，打算用这些来玩些什么。他从捡回来的垃圾堆里找到了不少火柴棍，便把这些火柴棍拼成了一个长度为<span lang="EN-US">n </span>的十进制数，每个数字的拼法如下图所示</span></p>
<p></p>
<p></p>
<p></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><b><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt">注意：每个数字占据的宽度和摆放方式是固定的，故以下情况均不合法。</span></b></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><b><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt"><img height="303" alt="" width="762" src="source/bzoj/3324/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMi8zLmpwZw==.jpg"/></span></b></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"></p>
<p></p>
<div align="left"><b><span style="font-size: 12pt"><img height="200" alt="" width="814" src="source/bzoj/3324/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMi8xLmpwZw==.jpg"/></span></b></div>
<p></p>
<div align="left"></div>
<div align="left"></div>
<p><span style="font-size: 12pt">拼完之后他好累，感觉再也不会拼了。</span></p>
<p></p>
<div align="left"><span style="font-size: 12pt">他对拼出来的数大小不满意，希望通过移动一些火柴棍的位置来把这个数变得尽量大。由于太累，他只能最多移动k 根火柴棍。而且由于数字的最低位放在墙边，他不能在该数的低位后面添加数字，但他可以在该数的前面添加数字。</span></div>
<div align="left"><span style="font-size: 12pt">你能帮他算出他移动火柴棍之后的数最大能是多大吗？</span></div>
<div align="left"><b><span style="font-size: 12pt">注意：火柴棍对于Fish 来说是很贵重的物品，所以不允许折断或丢弃火柴棍。</span></b></div>
<div align="left"><b><span style="font-size: 12pt">注意：火柴头的方向不影响数字的辨识，例如下面几种情况都是数字1         </span></b></div>
<div align="left"> </div>
<div align="left"><img height="196" alt="" width="600" src="source/bzoj/3324/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMi8yLmpwZw==.jpg"/></div></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt">输入仅含一行，分别是长度为<span lang="EN-US">n </span>的十进制数<span lang="EN-US">x </span>和最多移动火柴棍的数量<span lang="EN-US">k</span>。<span lang="EN-US">x </span>没有前导零。<span lang="EN-US"><br/>
</span>对于<span lang="EN-US">30% </span>的数据，<span lang="EN-US">1 &lt;= n &lt;= 10</span>，<span lang="EN-US">0 &lt;= k &lt;= 10</span>。<span lang="EN-US"><br/>
</span>对于<span lang="EN-US">100% </span>的数据，<span lang="EN-US">1 &lt;= n &lt;= 500</span>，<span lang="EN-US">0 &lt;=k &lt;=3500</span>。<span lang="EN-US"> <o:p></o:p></span></span></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; mso-outline-level: 2"><b><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt"><o:p></o:p></span></b> </p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt">输出仅一行，表示移动火柴棍之后的最大数。<span lang="EN-US"> <o:p></o:p></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample #1<br/>
3 2<br/>
<br/>
Sample #2<br/>
3 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Sample #1<br/>
17<br/>
<br/>
Sample #2<br/>
71<br/>
</span></div>

# Hint

<div class="content"><p></p><p>应上传者要求，此系列试题不公开,如有异议，本站将删除之。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

