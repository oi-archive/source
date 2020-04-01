
# Description

<div class="content"><div>&#34;经过精确的测量，整个桥梁可以被分为N段，从左往右标号1~N，每一段有一个&#39;稳定值&#39;来代表这一段的牢固程度-</div>
<div>-越牢固的地方，需要越大的代价去烧毁或拆毁，这个数列记为A1~An。这个稳定值介于1000~2000之间。详细的计</div>
<div>划分为两步：第一步，烧毁某些位置；第二步，拆掉某些位置。在第一步中，我们选择若干个位置，记为K个：Ap1</div>
<div>,Ap2,…,Apk，其中p1&lt;p2&lt;..&lt;pk，然后逐一烧毁这些位置。由于放火是有危险的，所以对于从左往右的第i个位置p</div>
<div>i，烧毁它的代价为i*Api。现在，桥的剩下的N-K个位置被烧成了K+1段--可能有些段为空。对于每一段，如果它的</div>
<div>所有Ai之和不足M，那么说明这一段自己会坍塌，不必管它；否则，我们需要逐一拆毁这些位置，设这段Ai之和为T</div>
<div>，当T&gt;M的时候我们就需要支付T的代价。两部分的代价加起来即为整个计划的总代价。整个计划一定会选取最优的</div>
<div>方案进行，也就是最小化总代价。目前记者还没有得到关于总代价的信息……不过全部的数据都有，你也可以自己</div>
<div>计算这个值。&#34;</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行是两个正整数N(&lt;=100000)和M（&lt;=2*10^8），含义如题目所述。 </div>
<div>第二行是N个用空格隔开的正整数，代表整个A数列。（1000&lt;=Ai&lt;=2000）</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一行一个正整数，之前所说的最小总代价。</div>
<div>N&lt;=100000，1000&lt;=Ai&lt;=2000</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 9<br/>
5 3 3 9 1 4 2 2 4 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
【样例解释】<br/>
选择从左往右第3、5、9位置烧掉即可（下标从1开始标号）。<br/>
如果选择3、6、9，则总代价为33，明显不优。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

