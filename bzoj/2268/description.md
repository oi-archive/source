
# Description

<div class="content"><p>Jonly is writing his first computer game. For the opening scene he wants to have the main character, Wormly, cross Bridgely, the bridge. Wormly is a worm made of b equal circular bubbles and L legs. At all times each leg has to be under one of the bubbles, and under each bubble there can be at most one leg. Bridgely was supposed to be composed of n planks with the width of each plank equal to the diameter of each of Wormly&#39;s bubbles. However, some of the planks are missing.</p>
<div class="p"><!----></div>
<p>At every moment, Wormly can do exactly one of the following:</p>
<ul>
    <li>Move one of its legs forward over any number of (possibly missing) planks. After the move, the leg should be on a plank and underneath one of Wormly&#39;s bubbles. A leg isn&#39;t allowed to overtake other legs.
    <div class="p"><!----></div>
    </li>
    <li>Move all of its bubbles forward one plank while its legs remain on the same planks. After the move each leg must still be under one of Wormly&#39;s bubbles.
    <div class="p"><!----></div>
    </li>
</ul>
<div class="p"><!----></div>
<div class="p"><!----></div>
<p><img alt="" src="/source/bzoj/2268/img/aHR0cDovL3V2YS5vbmxpbmVqdWRnZS5vcmcvY29udGVzdHMvMjY3LTRmZWVkNTgzL2ltYWdlcy9wOV8xLnBuZw==.png"/></p>
<p></p>
<div>Wormly 是一条虫子，它的身体有b个球和L条腿。任何时候，它的腿总是在某个球的下方，并且每个球下方至多一条腿。</div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">Wormly </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">想要过桥。这个桥由本来由</span><span lang="EN-US"><font face="Calibri">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">块板子组成，但有的板子不见了。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">每个时刻里，</span><span lang="EN-US"><font face="Calibri">wormly</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">可以做这些事：</span></font></p>
<p class="a" style="margin: 0cm 0cm 0pt 18pt; text-indent: -18pt; mso-char-indent-count: 0; mso-list: l0 level1 lfo1"><span lang="EN-US" style="mso-fareast-font-family: Calibri; mso-bidi-font-family: Calibri"><span style="mso-list: Ignore"><font face="Calibri" size="3">1、</font><span style="font: 7pt &#34;Times New Roman&#34;">  </span></span></span><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">向前移动一个脚到一块板子，要求不能越过前面的腿（图中</span><span lang="EN-US"><font face="Calibri">c</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">），不能落在消失的板子上（图中</span><span lang="EN-US"><font face="Calibri">a</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">）；</span></font></p>
<p class="a" style="margin: 0cm 0cm 0pt 18pt; text-indent: -18pt; mso-char-indent-count: 0; mso-list: l0 level1 lfo1"><span lang="EN-US" style="mso-fareast-font-family: Calibri; mso-bidi-font-family: Calibri"><span style="mso-list: Ignore"><font face="Calibri" size="3">2、</font><span style="font: 7pt &#34;Times New Roman&#34;">  </span></span></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri"><font size="3">把所有的球向前移动一格，腿不动。移完之后，每条腿必须还在某个球下。</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">一开始虫在最左的</span><span lang="EN-US"><font face="Calibri">b</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">块板子上，腿在最左的</span><span lang="EN-US"><font face="Calibri">L</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">块板子上，最后虫在最右的</span><span lang="EN-US"><font face="Calibri">b</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">块板子上，腿在最右的</span><span lang="EN-US"><font face="Calibri">L</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">块板子上。这个过程最少要多少时间？</span></font></p></div>

# Input

<div class="content"><p>On the first line a positive integer: the number of test cases, at most 100. After that per test case:</p>
<div class="p"><!----></div>
<ul>
    <li>One line with three integers L, b and n (1 ≤ L ≤ b ≤ n ≤ 1 000 000): the number of legs, the number of bubbles and the length of the bridge respectively.
    <div class="p"><!----></div>
    </li>
    <li>One line with a string consisting of n characters, either `<tt><font face="新宋体">0</font></tt>&#39; or `<tt><font face="新宋体">1</font></tt>&#39;, describing Bridgely. A one indicates a plank and a zero indicates a missing plank.
    <div class="p"><!----></div>
    </li>
</ul>
<div class="p"><!----></div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">T </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">测试数据组数</span><span lang="EN-US"><font face="Calibri">&lt;=100</font></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font face="Calibri" size="3"> L, b and n (1 ≤ L ≤ b ≤ n ≤ 1 000 000)</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">位</span><span lang="EN-US"><font face="Calibri">01</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">串，</span><span lang="EN-US"><font face="Calibri">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">代表有板子</span></font></p>
<p></p></div>

# Output

<div class="content"><p>Per test case:</p>
<ul>
    <li>One line with an integer: the minimum number of steps it takes Wormly to cross Bridgely. If it is impossible to get across while satisfying the constraints, the line must contain &#34;<tt><font face="新宋体">IMPOSSIBLE</font></tt>&#34; instead.</li>
</ul>
<center>Figure 1: In this example, the only possible move for the last leg is to position b. (The plank at position a is missing, so the leg cannot move there. To get to position c, the last leg would have to overtake the first leg.) Also, in this example, moving all the bubbles forward is not allowed because Wormly&#39;s last leg would end up without a bubble over it. </center>
<div class="p"><!----></div>
<p>Now Jonly is wondering how long the animation takes until Wormly reaches the end of Bridgely. Initially Wormly&#39;s bubbles are directly above the leftmost b planks of the bridge and its legs are on the leftmost L planks. At the end of the animation Wormly&#39;s bubbles have to be directly above the rightmost b planks and its legs have to be on the rightmost L planks.</p>
<div class="p"><!----></div>
<p>The left- and rightmost L planks of Bridgely are not missing.</p>
<div class="p"><!----></div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">IMPOSSIBLE</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">或者是最小的通过时间</span><span lang="EN-US"><font face="Calibri">.</font></span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 2 2<br/>
11<br/>
2 3 5<br/>
11011<br/>
1 3 5<br/>
11011<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
IMPOSSIBLE<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第</span><span lang="EN-US"><font face="Calibri">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">个样例：移动腿</span><span lang="EN-US"><font face="Calibri">-</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">移动球</span><span lang="EN-US"><font face="Calibri">-</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">移动腿</span><span lang="EN-US"><font face="Calibri">-</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">移动球</span><span lang="EN-US"><font face="Calibri">-</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">移动腿</span><span lang="EN-US"><font face="Calibri"> 5</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">步</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">鸣谢SJTU YYD</span></font></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

