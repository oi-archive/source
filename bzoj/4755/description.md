
# Description

<div class="content"><div>JYY有两个长度均为N的字符串A和B。</div>
<div>一个“扭动字符串S(i,j,k)由A中的第i个字符到第j个字符组成的子串</div>
<div>与B中的第j个字符到第k个字符组成的子串拼接而成。</div>
<div>比如，若A=’XYZ’，B=’UVW’，则扭动字符串S(1,2,3)=’XYVW’。</div>
<div>JYY定义一个“扭动的回文串”为如下情况中的一个：</div>
<div>1.A中的一个回文串；</div>
<div>2.B中的一个回文串；</div>
<div>3.或者某一个回文的扭动字符串S(i,j,k)</div>
<div>现在JYY希望找出最长的扭动回文串。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数N。</div>
<div>第二行包含一个长度为N的由大写字母组成的字符串A。</div>
<div>第三行包含一个长度为N的由大写字母组成的字符串B。</div>
<div>1≤N≤10^5。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出的第一行一个整数，表示最长的扭动回文串。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
ABCDE<br/>
BAECB</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
最佳方案中的扭动回文串如下所示（不在回文串中的字符用.表示）：<br/>
.BC..<br/>
..ECB</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

