
# Description

<div class="content"><p><span style="font-size: medium">Every morning, Farmer John&#39;s N (1 &lt;= N &lt;= 25,000) cows all line up for milking. In an effort to streamline the milking process, FJ has designed a two-stage milking process where the line of cows progresses through two barns in sequence, with milking taking part sequentially in both barns. Farmer John milks cows one by one as they go through the first barn, and his trusty sidekick Farmer Rob milks the cows (in the same order) as they are released from the first barn and enter the second barn. Unfortunately, Farmer John&#39;s insistence that the cows walk through both barns according to a single ordering leads to some inefficiencies. For example, if Farmer John takes too long to milk a particular cow, Farmer Rob might end up sitting idle with nothing to do for some time. On the other hand, if Farmer John works too fast then we might end up with a long queue of cows waiting to enter the second barn. Please help Farmer John decide on the best possible ordering of cows to use for the milking, so that the last cow finishes milking as early as possible. For each cow i we know the time A(i) required for milking in the first barn and the time B(i) required for milking in the second barn. Both A(i) and B(i) are in the range 1...20,000. </span></p>
<div><span style="font-size: medium">每天早晨，约翰的N(1≤N≤25000)头奶牛都排成一列，逐一挤奶．为了提高挤奶的速率，</span></div>
<div><span style="font-size: medium">约翰把整个挤奶过程划分成两道工序，每头牛都得连续地完成这些挤奶工序．奶牛们一个接一个地进入挤奶的牛棚，约翰负责实行第一道工序，第二道工序则让他的好友萝卜帮助完成．并且，如果某头奶牛先于另一头奶牛开始进行第一道工序，那么她开始第二道工序的时间也一定在那一头奶牛之前．    约翰发现，如果奶牛们按某种顺序排队进行挤奶，那么可能会在排队等待上多花很多的时间．比方说，如果约翰要花很长时间才能完成某头奶牛挤奶时的第一道工序，那么萝卜可能会有一段时间没有事做．当煞，如果约翰的工作完成得太快，萝}、面前就会有很多奶牛排起长队．    请你帮助约翰计算一下，如果按照最优的排队方式，最少需要多少时间才能把所有奶牛都挤过奶．对于每头奶牛，我们都知道在她身上完成第一道工序所需的时间Ai，以及完成第二道工序的时间Bi.   1≤Ai，Bi≤20000.</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, N. </span></p>
<p><span style="font-size: medium">* Lines 2..1+N: Line i+1 contains two space-separated integers A(i) and B(i) for cow i.</span></p>
<div><span style="font-size: medium">第1行一个整数N．接下来N行，每行两个整数表示第i头牛的Ai，Bi值．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The minimum possible time it takes to milk all the cows, if we order them optimally. </span></p>
<div><span style="font-size: medium">    输出按照最优方案排队后，最少需要多少时间才能完成对所有奶牛的挤奶．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 2<br/>
7 4<br/>
3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">16<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; font-size: 10.5pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">   </span><span style="font-family: 宋体; font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">把奶牛们按照</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; font-size: 10.5pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">3</span><span style="font-family: 宋体; font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; font-size: 10.5pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">1</span><span style="font-family: 宋体; font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; font-size: 10.5pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">2</span><span style="font-family: 宋体; font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">的顺序排队，这样挤奶总共花费</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; font-size: 10.5pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">16</span><span style="font-family: 宋体; font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">个单位时间．</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

