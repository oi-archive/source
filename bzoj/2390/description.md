
# Description

<div class="content"><div>最近小风沉醉于研究数。</div>
<div>由于他对0情有独钟(经常暴0…)，因此他认为非0数都是不和谐的。</div>
<div>于是他研究上了二进制数，因为里面的非0数只有1！</div>
<div>即便如此，1还是令他很不爽…</div>
<div>于是他想把所有的k位二进制数0、1、…2k -1划分成m组，每一组都是连续的一些数。设Si(1≤i≤m)表示第i组中所有数中的1的个数和。</div>
<div>小风想知道，所有的划分方案中，max{Si} 的最小值是多少。</div></div>

# Input

<div class="content"><div>有且仅有一行：两个数k、m，用一个空格分开。</div></div>

# Output

<div class="content"><div>有且仅有一行：一个数，表示max{Si} 的最小值</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例解释】<br/><br/>
 分成如下4组最优：<br/><br/>
 000 001 010 011<br/><br/>
 100 101<br/><br/>
 110<br/><br/>
 111<br/><br/>
 S1 = 4、S2 = 3、S3 = 2、S4 = 3<br/><br/>
 max{Si} = 4     <br/><br/>
【数据规模】<br/><br/>
20%的数据中， k ≤ 20<br/><br/>
100%的数据中，1 ≤ k ≤ 100, 1 ≤ m ≤ 100 且 m ≤2k</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

