
# Description

<div class="content"><p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">打地鼠是这样的一个游戏：地面上有一些地鼠洞，地鼠们会不时从洞里探出头来很短时间后又缩回洞中。玩家的目标是在地鼠伸出头时，用锤子砸其头部，砸到的地鼠越多分数也就越高。</font></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">游戏中的锤子每次只能打一只地鼠，如果多只地鼠同时探出头，玩家只能通过多次挥舞锤子的方式打掉所有的地鼠。你认为这锤子太没用了，所以你改装了锤子，增加了锤子与地面的接触面积，使其每次可以击打一片区域。如果我们把地面看做</span><span lang="EN-US"><font face="Times New Roman">M*N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的方阵，其每个元素都代表一个地鼠洞，那么锤子可以覆盖</span><span lang="EN-US"><font face="Times New Roman">R*C</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">区域内的所有地鼠洞。但是改装后的锤子有一个缺点：每次挥舞锤子时，对于这</span><span lang="EN-US"><font face="Times New Roman">R*C</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的区域中的所有地洞，锤子会打掉恰好一只地鼠。也就是说锤子覆盖的区域中，每个地洞必须至少有</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只地鼠，且如果某个地洞中地鼠的个数大于</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，那么这个地洞只会有</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只地鼠被打掉，因此每次挥舞锤子时，恰好有</span><span lang="EN-US"><font face="Times New Roman">R*C</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只地鼠被打掉。由于锤子的内部结构过于精密，因此在游戏过程中你不能旋转锤子（即不能互换</span><span lang="EN-US"><font face="Times New Roman">R</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">C</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">）。</span></font></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">你可以任意更改锤子的规格（即你可以任意规定</span><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><font face="Times New Roman">R</font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><font face="Times New Roman">C</font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的大小），但是改装锤子的工作只能在打地鼠前进行（即你不可以打掉一部分地鼠后，再改变锤子的规格）。你的任务是求出要想打掉所有的地鼠，至少需要挥舞锤子的次数。</span></font></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">Hint</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">：由于你可以把锤子的大小设置为</span><span lang="EN-US"><font face="Times New Roman">1*1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，因此本题总是有解的。</span></font></p>
<p class="NOI0" style="margin: 13pt 0cm"></p>
<p></p></div>

# Input

<div class="content"><p class="NOI0" style="margin: 13pt 0cm"> <font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行包含两个正整数</span><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><font face="Times New Roman">M</font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><font face="Times New Roman">N</font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">；</span></font></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">下面</span><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><font face="Times New Roman">M</font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行每行</span><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><font face="Times New Roman">N</font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个正整数描述地图，每个数字表示相应位置的地洞中地鼠的数量。</span></font></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"></p>
<p></p></div>

# Output

<div class="content"><p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">输出一个整数，表示最少的挥舞次数。</font></span></p>
<p class="NOI2" style="margin: 0cm 0cm 0pt"></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
<br/>
1 2 1<br/>
<br/>
2 4 2<br/>
<br/>
1 2 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
4<br/>
<br/>
【样例说明】<br/>
<br/>
使用2*2的锤子，分别在左上、左下、右上、右下挥舞一次。<br/>
<br/>
【数据规模和约定】<br/>
<br/>
<br/>
对于100%的数据，1&lt;=M,N&lt;=100，其他数据不小于0，不大于10^5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=第一轮Day1">第一轮Day1</a></p></div>

