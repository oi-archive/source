
# Description

<div class="content"><p><span style="font-size: medium">Farmer John went to cut some wood and left N (2 &lt;= N &lt;= 100,000) cows eating the grass, as usual. When he returned, he found to his horror that the cows were in his garden eating his beautiful flowers. Wanting to minimize the subsequent damage, FJ decided to take immediate action and transport the cows back to their barn. Each cow i is at a location that is Ti minutes (1 &lt;= Ti &lt;= 2,000,000) away from the barn. Furthermore, while waiting for transport, she destroys Di (1 &lt;= Di &lt;= 100) flowers per minute. No matter how hard he tries,FJ can only transport one cow at a time back to the barn. Moving cow i to the barn requires 2*Ti minutes (Ti to get there and Ti to return). Write a program to determine the order in which FJ should pick up the cows so that the total number of flowers destroyed is minimized.</span></p>
<div><span style="font-size: medium">   约翰留下他的N只奶牛上山采木．他离开的时候，她们像往常一样悠闲地在草场里吃草．可</span><span style="font-size: medium">是，当他回来的时候，他看到了一幕惨剧：牛们正躲在他的花园里，啃食着他心爱的美丽花朵！为了使接下来花朵的损失最小，约翰赶紧采取行动，把牛们送回牛棚． 牛们从1到N编号．第i只牛所在的位置距离牛棚Ti(1≤Ti《2000000)分钟的路程，而在约翰开始送她回牛棚之前，她每分钟会啃食Di(1≤Di≤100)朵鲜花．无论多么努力，约翰一次只能送一只牛回棚．而运送第第i只牛事实上需要2Ti分钟，因为来回都需要时间．    写一个程序来决定约翰运送奶牛的顺序，使最终被吞食的花朵数量最小．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer </span></p>
<p><span style="font-size: medium">N * Lines 2..N+1: Each line contains two space-separated integers, Ti and Di, that describe a single cow&#39;s characteristics</span></p>
<p></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行输入</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，之后</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行每行输入两个整数</span><span lang="EN-US"><font face="Times New Roman">Ti</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">Di</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．</span></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer that is the minimum number of destroyed flowers </span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">一个整数，表示最小数量的花朵被吞食．</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
3 1<br/>
2 5<br/>
2 3<br/>
3 2<br/>
4 1<br/>
1 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">86<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">约翰用</span><span lang="EN-US"><font face="Times New Roman">6</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的顺序来运送他的奶牛．</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

