
# Description

<div class="content"><p><span style="font-size: medium">Bessie and Bonnie have found a treasure chest full of marvelous gold coins! Being cows, though, they can&#39;t just walk into a store and buy stuff, so instead they decide to have some fun with the coins. The N (1 &lt;= N &lt;= 5,000) coins, each with some value C_i (1 &lt;= C_i &lt;= 5,000) are placed in a straight line. Bessie and Bonnie take turns, and for each cow&#39;s turn, she takes exactly one coin off of either the left end or the right end of the line. The game ends when there are no coins left. Bessie and Bonnie are each trying to get as much wealth as possible for themselves. Bessie goes first. Help her figure out the maximum value she can win, assuming that both cows play optimally. Consider a game in which four coins are lined up with these values: 30 25 10 35 Consider this game sequence: Bessie Bonnie New Coin Player Side CoinValue Total Total Line Bessie Right 35 35 0 30 25 10 Bonnie Left 30 35 30 25 10 Bessie Left 25 60 30 10 Bonnie Right 10 60 40 -- This is the best game Bessie can play. </span></p>
<div><span style="font-size: medium">  贝西和邦妮找到了一个藏宝箱，里面都是金币！但是身为两头牛，她们不能到商店里把</span><span style="font-size: medium">金币换成好吃的东西，于是她们只能用这些金币来玩游戏了。</span></div>
<div><span style="font-size: medium">    藏宝箱里一共有N枚金币，第i枚金币的价值是Ci。贝西和邦妮把金币排成一条直线，她</span><span style="font-size: medium">们轮流取金币，看谁取到的钱最多。贝西先取，每次只能取一枚金币，而且只能选择取直线</span><span style="font-size: medium">两头的金币，不能取走中间的金币。当所有金币取完之后，游戏就结束了。</span></div>
<div><span style="font-size: medium">    贝西和邦妮都是非常聪明的，她们会采用最好的办法让自己取到的金币最多。请帮助贝</span><span style="font-size: medium">西计算一下，她能拿到多少钱？</span></div></div>

# Input

<div class="content"><p>* Line 1: A single integer: N * Lines 2..N+1: Line i+1 contains a single integer: C_i</p>
<div><span style="font-size: medium">第一行：单个整数N，表示硬币的数量，1&lt;=N≤5000</span></div>
<div><span style="font-size: medium">第二行到第N+1行：第i+l行有一个整数Ci，代表第i块硬币的价值，1≤Ci≤5000</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, which is the greatest total value Bessie can win if both cows play optimally. </span></p>
<div><span style="font-size: medium">  第一行：单个整数，表示如果双方都按最优策略玩游戏，先手可以拿到的最大价值</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
30<br/>
25<br/>
10<br/>
35<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">60<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">  (</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">贝西最好的取法是先取</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">35</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">，然后邦妮会取</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">30</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">，贝西再取</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">25</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">，邦妮最后取</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">10)</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

