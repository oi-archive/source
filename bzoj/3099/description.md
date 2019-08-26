
# Description

<div class="content"><p><span style="font-size: medium">这天天气不错，hzhwcmhf神犇给VFleaKing出了一道题：<br/>
给你一个长度为N的字符串S，求有多少个不同的长度为L的子串。<br/>
子串的定义是S[l]、S[l + 1]、... S[r]这样连续的一段。<br/>
两个字符串被认为是不同的当且仅当某个位置上的字符不同。</span></p>
<p><span style="font-size: medium">VFleaKing一看觉得这不是Hash的裸题么！于是果断写了哈希 + 排序。<br/>
而hzhwcmhf神犇心里自然知道，这题就是后缀数组的height中 &lt; L的个数 + 1，就是后缀自动机上代表的长度区间包含L的结点个数，就是后缀树深度为L的结点的数量。<br/>
但是hzhwcmhf神犇看了看VFleaKing的做法表示非常汗。于是想卡掉他。</span></p>
<p><span style="font-size: medium">VFleaKing使用的是字典序哈希，其代码大致如下：<br/>
u64 val = 0;<br/>
for (int i = 0; i &lt; l; i++)<br/>
 val = (val * base + s[i] - &#39;a&#39;) % Mod;<br/>
u64是无符号int64，范围是[0, 2^64)。<br/>
base是一个常量，VFleaKing会根据心情决定其值。<br/>
Mod是int32范围内的素数。即Mod范围是[0, 2^31)，且是个素数。<br/>
VFleaKing还求出来了base ^ l % Mod，即base的l次方除以Mod的余数，这样就能方便地求出所有长度为L的子串的哈希值。<br/>
然后VFleaKing给哈希值排序，去重，求出有多少个不同的哈希值，把这个数作为结果。<br/>
但是VFleaKing意识到这样会被坑，于是采用了两个Mod来解决问题。两个Mod模出来的值都相同才被认为是相同。<br/>
其算法的C++代码如下：</span></p>
<p><span style="font-size: medium">typedef unsigned long long u64;<br/>
typedef pair&lt;int, int&gt; PII;</span></p>
<p><span style="font-size: medium">const int MaxN = 100000;</span></p>
<p><span style="font-size: medium">inline int hash_handle(<br/>
  const char *s, const int &amp;n, const int &amp;l, const int &amp;base,<br/>
  const int &amp;mod1, const int &amp;mod2)<br/>
{<br/>
 int li_n;<br/>
 static PII li[MaxN];<br/>
 u64 hash_pow_l;<br/>
 u64 val;</span></p>
<p><span style="font-size: medium"> hash_pow_l = 1;<br/>
 for (int i = 1; i &lt;= l; i++)<br/>
  hash_pow_l = (hash_pow_l * base) % mod1;</span></p>
<p><span style="font-size: medium"> li_n = 0;<br/>
 val = 0;<br/>
 for (int i = 0; i &lt; l; i++)<br/>
  val = (val * base + s[i] - &#39;a&#39;) % mod1;<br/>
 li[li_n++].first = val;<br/>
 for (int i = l; i &lt; n; i++)<br/>
 {<br/>
  val = (val * base + s[i] - &#39;a&#39;) % mod1;<br/>
  val = (val + mod1 - ((s[i - l] - &#39;a&#39;) * hash_pow_l) % mod1) % mod1;<br/>
  li[li_n++].first = val;<br/>
 }</span></p>
<p><span style="font-size: medium"> hash_pow_l = 1;<br/>
 for (int i = 1; i &lt;= l; i++)<br/>
  hash_pow_l = (hash_pow_l * base) % mod2;</span></p>
<p><span style="font-size: medium"> li_n = 0;<br/>
 val = 0;<br/>
 for (int i = 0; i &lt; l; i++)<br/>
  val = (val * base + s[i] - &#39;a&#39;) % mod2;<br/>
 li[li_n++].second = val;<br/>
 for (int i = l; i &lt; n; i++)<br/>
 {<br/>
  val = (val * base + s[i] - &#39;a&#39;) % mod2;<br/>
  val = (val + mod2 - ((s[i - l] - &#39;a&#39;) * hash_pow_l) % mod2) % mod2;<br/>
  li[li_n++].second = val;<br/>
 }</span></p>
<p><span style="font-size: medium"> sort(li, li + li_n);<br/>
 li_n = unique(li, li + li_n) - li;<br/>
 return li_n;<br/>
}</span></p>
<p><span style="font-size: medium">hzhwcmhf当然知道怎么卡啦！但是他想考考你。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">没有输入。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">你需要输出一组数据使得VFleaKing的代码WA掉。我们会使用Special Judge检查你的结果的正确性。<br/>
输出文件共两行。<br/>
第一行两个用空格隔开的数n、l。<br/>
第二行是一个长度为n的字符串。只能包含&#39;a&#39;~&#39;z&#39;。<br/>
需要保证1 &lt;= n &lt;= 10^5, 1 &lt;= l &lt;= n，<br/>
不符合以上格式会WA。<br/>
不要有多余字符，很可能导致你WA。</font></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">没有<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 4<br/>
buaabuaa<br/>
（当然这个输出是会WA的）<br/>
</span></div>

# Hint

<div class="content"><p></p><p>其实出题人并不知道怎么做……只是把这题挂在这里希望有人能给个解答。<br/><br/>
如果这个问题解决了hash应该能算是正式被hack了。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=VFleaKing &amp; hzhwcmhf
">VFleaKing &amp; hzhwcmhf<br/>
</a></p></div>

