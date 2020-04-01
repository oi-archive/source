
# Description

<div class="content"><div>Mushroom最近看上了一个漂亮妹纸。他选择一种非常经典的手段来表达自己的心意——写情书。考虑到自己的表达能力，Mushroom决定不手写情书。他从网上找到了两篇极佳的情书，打算选择其中共同的部分。另外，Mushroom还有个一个情敌Ertanis，此人也写了封情书给妹子。</div>
<div>Mushroom不希望自己的情书中完整的出现了情敌的情书。（这样抄袭的事情就暴露了）。</div>
<div>Mushroom把两封情书分别用字符串s1和s2来表示，Ertanis的情书用字符串s3来表示，他要截取的部分用字符串w表示。</div>
<div>需满足：</div>
<div>1、w是s1的子串</div>
<div>2、w是s2的子串</div>
<div>3、s3不是w的子串</div>
<div>4、w的长度应尽可能大</div>
<div>所谓子串是指：在字符串中连续的一段</div>
<div>【输入】</div>
<div>输入文件为girl.in</div>
<div>输入有三行，第一行为一个字符串s1第二行为一个字符串s2， </div>
<div>第三行为一个字符串s3。输入仅含小写字母，字符中间不含空格。</div>
<div>【输出】</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>输出文件为girl.out</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>输出仅有一行，为w的最大可能长度，如w不存在，则输出0。</div>
<div>【输入样例】</div>
<div>abcdef</div>
<div>abcf</div>
<div>bc</div>
<div>【输出样例】</div>
<div>2</div>
<div>【样例解释】</div>
<div>s1和s2的公共子串有abc,ab,bc,a,b,c,f，其中abc,bc包含子串bc不合法，所以最长的合法子串为ab。</div>
<div>【数据规模】</div>
<div>对于30%的数据：1&lt;=s1、s2、s3的长度&lt;=500</div>
<div>对于60%的数据：1&lt;=s1、s2、s3的长度&lt;=5000</div>
<div>对于100%的数据：1&lt;=s1、s2的长度&lt;=50000,1&lt;=s3的长度&lt;=10000</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入有三行，第一行为一个字符串s1第二行为一个字符串s2， </div>
<div>
<div>第三行为一个字符串s3。输入仅含小写字母，字符中间不含空格。</div>
</div>
<p></p></div>

# Output

<div class="content"><div>输出仅有一行，为w的最大可能长度，如w不存在，则输出0。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">abcdef<br/>
abcf<br/>
bc<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
【样例解释】<br/>
s1和s2的公共子串有abc,ab,bc,a,b,c,f，其中abc,bc包含子串bc不合法，所以最长的合法子串为ab。<br/>
</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据：1&lt;=s1、s2的长度&lt;=50000,1&lt;=s3的长度&lt;=10000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

