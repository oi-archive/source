
# Description

<div class="content"><p> <span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">小A有一个1-2^N的排列A[1..2^N],他希望将A数组从小到大排序,小A可以执行的操作有N种,每种操作最多可以执行一次,对于所有的i(1&lt;=i&lt;=N),第i中操作为将序列从左到右划分为2^{N-i+1}段,每段恰好包括2^{i-1}个数,然后整体交换其中两段.小A想知道可以将数组A从小到大排序的不同的操作序列有多少个,小A认为两个操作序列不同,当且仅当操作个数不同,或者至少一个操作不同(种类不同或者操作位置不同).</span></p>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">  下面是一个操作事例:</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">  N=3,A[1..8]=[3,6,1,2,7,8,5,4].</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">  第一次操作,执行第3种操作,交换A[1..4]和A[5..8],交换后的A[1..8]为[7,8,5,4,3,6,1,2].</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">  第二次操作,执行第1种操作,交换A[3]和A[5],交换后的A[1..8]为[7,8,3,4,5,6,1,2].</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">  第三次操作,执行第2中操作,交换A[1..2]和A[7..8],交换后的A[1..8]为[1,2,3,4,5,6,7,8].</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div></div>

# Input

<div class="content"><p><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">第一行,一个整数N</span></p>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">第二行,2^N个整数,A[1..2^N]</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div>
</div></div>

# Output

<div class="content"><p><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">一个整数表示答案<br/>
</span></p>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div></div>

# Sample Input

<div class="content"><span class="sampledata">  3<br/>
  7 8 5 6 1 2 4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
</span></div>

# Hint

<div class="content"><p></p><p>100%的数据, 1&lt;=N&lt;=12.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 感谢ZKY制作非官方数据">Round 1 感谢ZKY制作非官方数据</a></p></div>

