
# Description

<div class="content"><p><span lang="EN-US">  </span><span style="font-family: 宋体;">想象一下火车有</span><span lang="EN-US">N</span><span style="font-family: 宋体;">个座位，</span><span lang="EN-US">N</span><span style="font-family: 宋体;">个座位相当于数轴上的１至Ｎ共Ｎ个整点，第</span><span lang="EN-US">1</span><span style="font-family: 宋体;">个座位在整点</span><span lang="EN-US">1</span><span style="font-family: 宋体;">处，第</span><span lang="EN-US">2</span><span style="font-family: 宋体;">个座位在整点</span><span lang="EN-US">2</span><span style="font-family: 宋体;">处，。。。第</span><span lang="EN-US">N</span><span style="font-family: 宋体;">个座位在整点</span><span lang="EN-US">N</span><span style="font-family: 宋体;">处。</span><span lang="EN-US"> </span><span style="font-family: 宋体;">有</span><span lang="EN-US">N</span><span style="font-family: 宋体;">个奶牛排好队，要登陆坐火车，第</span><span lang="EN-US">N</span><span style="font-family: 宋体;">头奶牛在数轴的整点</span><span lang="EN-US">0</span><span style="font-family: 宋体;">处，第</span><span lang="EN-US">N-1</span><span style="font-family: 宋体;">头奶牛在数轴的整点</span><span lang="EN-US">-1</span><span style="font-family: 宋体;">处，。。。。第</span><span lang="EN-US">1</span><span style="font-family: 宋体;">头奶牛在数轴的整点</span><span lang="EN-US">-N+1</span><span style="font-family: 宋体;">处。第</span><span lang="EN-US">i</span><span style="font-family: 宋体;">头奶牛的座位号是</span><span lang="EN-US">Si</span><span style="font-family: 宋体;">。注意：每头奶牛都有唯一的一个座位，不会出现多头奶牛有相同的座位号。</span><span lang="EN-US"> </span></p>
<p class="MsoNormal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">在每一秒钟，奶牛会向右移动一步到达下一个整点，前提是没有奶牛挡住它。</span><span lang="EN-US"> </span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">当第</span><span lang="EN-US">i</span><span style="font-family:
宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">头奶牛到达它的座位</span><span lang="EN-US">Si</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">时，它需要花费</span><span lang="EN-US">Ti</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">秒去把行李放到头顶的行李架上，然后坐到自己的位置上，在次过程中，由于火车通道很窄，所以在第</span><span lang="EN-US">i</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">头奶牛坐到自己座位之前，在它左边的所有奶牛都不能动，要等奶牛</span><span lang="EN-US">i</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">放好行李坐好后才能动。</span><span lang="EN-US">      </span></p>
<p class="MsoNormal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">现在的问题是，至少要多少秒之后，所有的奶牛都能做到自己的座位上？</span><span lang="EN-US"> </span></p></div>

# Input

<div class="content"><p><span lang="EN-US" style="text-indent: 10.5pt;"> </span><span style="text-indent: 10.5pt; font-family: 宋体;">第一行，一个整数</span><span lang="EN-US" style="text-indent: 10.5pt;">N</span><span style="text-indent: 10.5pt; font-family: 宋体;">。</span><span lang="EN-US" style="text-indent: 10.5pt;">1 &lt;= N &lt;= 200000</span><span style="text-indent: 10.5pt; font-family: 宋体;">。</span><span lang="EN-US" style="text-indent: 10.5pt;"> </span></p>
<p class="MsoNormal"><span lang="EN-US"> </span><span style="font-family: 宋体;">接下来有</span><span lang="EN-US">N</span><span style="font-family: 宋体;">行，第</span><span lang="EN-US">i</span><span style="font-family: 宋体;">行有两个整数</span><span lang="EN-US">Si</span><span style="font-family: 宋体;">和</span><span lang="EN-US">Ti,</span><span style="font-family: 宋体;">表示第</span><span lang="EN-US">i</span><span style="font-family: 宋体;">头奶牛的参数。所有</span><span lang="EN-US">Ti</span><span style="font-family: 宋体;">之和不超过</span><span lang="EN-US">10^9</span><span style="font-family: 宋体;">。</span><span lang="EN-US">    </span></p></div>

# Output

<div class="content"><p><span style="font-family: 宋体;">一个整数。</span><span lang="EN-US"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 5<br/>
3 10<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">19<br/>
 </span></div>

# Hint

<div class="content"><p></p><p> OUTPUT DETAILS: After one step, they will all move 1 to the right and cow 3 will reach her seat: 123 123 Cow 3 takes 5 seconds to sit down, at which point she effectively disappears. 12 123 It takes 3 more seconds for cows 1 and 2 to reach their desired seats: 12 123 It takes 5 seconds for cow 1 to sit down and 10 seconds for cow 2 to sit down, so that&#39;s 10 seconds total. In total this took 1 + 5 + 3 + 10 = 19 seconds. </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

