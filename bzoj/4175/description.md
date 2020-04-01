
# Description

<div class="content"><p> <span style="text-indent: 21pt; font-family: 宋体;">小</span><span lang="EN-US" style="text-indent: 21pt;">G</span><span style="text-indent: 21pt; font-family: 宋体;">是一个商人，他有一个电话本。电话本上记下了许多联系人，如</span><span lang="EN-US" style="text-indent: 21pt;">timesqr</span><span style="text-indent: 21pt; font-family: 宋体;">、</span><span lang="EN-US" style="text-indent: 21pt;">orzyhb</span><span style="text-indent: 21pt; font-family: 宋体;">等等。不过</span><span lang="EN-US" style="text-indent: 21pt;">Tony</span><span style="text-indent: 21pt; font-family: 宋体;">对其中的某个联系人的名字</span><span lang="EN-US" style="text-indent: 21pt;">S</span><span style="text-indent: 21pt; font-family: 宋体;">特别感兴趣，他从中提取出了这个联系人的名字中的所有片段，如提取出</span><span lang="EN-US" style="text-indent: 21pt;">orz</span><span style="text-indent: 21pt; font-family: 宋体;">的</span><span lang="EN-US" style="text-indent: 21pt;">   o</span><span style="text-indent: 21pt; font-family: 宋体;">、</span><span lang="EN-US" style="text-indent: 21pt;">r</span><span style="text-indent: 21pt; font-family: 宋体;">、</span><span lang="EN-US" style="text-indent: 21pt;">z</span><span style="text-indent: 21pt; font-family: 宋体;">、</span><span lang="EN-US" style="text-indent: 21pt;">or</span><span style="text-indent: 21pt; font-family: 宋体;">、</span><span lang="EN-US" style="text-indent: 21pt;">rz</span><span style="text-indent: 21pt; font-family: 宋体;">、</span><span lang="EN-US" style="text-indent: 21pt;">orz</span><span style="text-indent: 21pt; font-family: 宋体;">等等。现在他想请你统计有多少个长度为</span><span lang="EN-US" style="text-indent: 21pt;">k</span><span style="text-indent: 21pt; font-family: 宋体;">的片段对</span><span lang="EN-US" style="text-indent: 21pt;">(P[1], P[2], P[3], ..., P[k])</span><span style="text-indent: 21pt; font-family: 宋体;">，使得在该片段对中所有片段在</span><span lang="EN-US" style="text-indent: 21pt;">S</span><span style="text-indent: 21pt; font-family: 宋体;">中出现次数之和为他的幸运数</span><span lang="EN-US" style="text-indent: 21pt;">m</span><span style="text-indent: 21pt; font-family: 宋体;">？注意两个片段对不同当且仅当两个片段对的某一位的片段不同，两个片段不同当且仅当这两个片段在</span><span lang="EN-US" style="text-indent: 21pt;">S</span><span style="text-indent: 21pt; font-family: 宋体;">中的位置不同<br/>
</span></p>
<p class="MsoNormal"></p></div>

# Input

<div class="content"><p><span style="font-family: 宋体;">第一行两个整数</span><span lang="EN-US">k</span><span style="font-family: 宋体;">和</span><span lang="EN-US">m</span><span style="font-family: 宋体;">，意义见题目描述；<span style="font-family: 宋体;">第二行给出一个字符串表示</span><span lang="EN-US">Tony</span><span style="font-family: 宋体;">喜欢的联系人名字</span><span lang="EN-US">S</span><span style="font-family: 宋体;">。</span></span></p>
<p class="MsoNormal"></p>
<p class="MsoNormal"></p></div>

# Output

<div class="content"><p><span style="font-family: 宋体;">输出一行一个整数</span><span lang="EN-US">ans</span><span style="font-family: 宋体;">，表示答案模</span><span lang="EN-US">1005060097</span><span style="font-family: 宋体;">。<br/>
</span></p>
<p class="MsoNormal"></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
aaaaa</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><p>【样例解释】</p><br/>
<div></div><br/>
<div>符合要求的片段对一共有6种（用[p]s表示起始位置为p的s片段）：</div><br/>
<div></div><br/>
<div>([1]aaaa, [1]aaaaa, [1]aaaaa)、([1]aaaaa, [1]aaaa, [1]aaaaa)、</div><br/>
<div></div><br/>
<div>([1]aaaaa, [1]aaaaa, [1]aaaa)、([2]aaaa, [1]aaaaa, [1]aaaaa)、</div><br/>
<div></div><br/>
<div>([1]aaaaa, [2]aaaa, [1]aaaaa)、([1]aaaaa, [1]aaaaa, [2]aaaa)。</div><br/>
<div></div><br/>
<div>【数据范围】</div><br/>
<div></div><br/>
<div>设n表示联系人的名字的长度，联系人的名字只包含小写字母。</div><br/>
<div></div><br/>
<div>对于10%的数据，1 &lt;= n &lt;= 100, k = 1。</div><br/>
<div></div><br/>
<div>对于40%的数据，1 &lt;= n &lt;= 100, k = 2。</div><br/>
<div></div><br/>
<div>对于70%的数据，1 &lt;= n &lt;= 100000, 1 &lt;= k &lt;= 10。</div><br/>
<div></div><br/>
<div>对于100%的数据，1 &lt;= n &lt;= 100000, 1 &lt;= k &lt;= 100000, 1 &lt;= m &lt;= n。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

