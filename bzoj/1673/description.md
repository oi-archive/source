
# Description

<div class="content"><p><span style="font-size: medium">Farmer John has a balance for weighing the cows. He also has a set of N (1 &lt;= N &lt;= 1000) weights with known masses (all of which fit in 31 bits) for use on one side of the balance. He places a cow on one side of the balance and then adds weights to the other side until they balance. (FJ cannot put weights on the same side of the balance as the cow, because cows tend to kick weights in his face whenever they can.) The balance has a maximum mass rating and will break if FJ uses more than a certain total mass C (1 &lt;= C &lt; 2^30) on one side. The weights have the curious property that when lined up from smallest to biggest, each weight (from the third one on) has at least as much mass as the previous two combined. FJ wants to determine the maximum mass that he can use his weights to measure exactly. Since the total mass must be no larger than C, he might not be able to put all the weights onto the scale. Write a program that, given a list of weights and the maximum mass the balance can take, will determine the maximum legal mass that he can weigh exactly. </span></p>
<div><span style="font-size: medium">    约翰有一架用来称牛的体重的天平．与之配套的是N(1≤N≤1000)个已知质量的砝码（所</span><span style="font-size: medium">有砝码质量的数值都在31位二进制内）．每次称牛时，他都把某头奶牛安置在天平的某一边，</span><span style="font-size: medium">然后往天平另一边加砝码，直到天平平衡，于是此时砝码的总质量就是牛的质量（约翰不能把砝码放到奶牛的那边，因为奶牛不喜欢称体重，每当约翰把砝码放到她的蹄子底下，她就会尝试把砝码踢到约翰脸上）．天平能承受的物体的质量不是无限的，当天平某一边物体的质量大于C(1≤C&lt;230)时，天平就会被损坏．    砝码按照它们质量的大小被排成一行．并且，这一行中从第3个砝码开始，每个砝码的质量至少等于前面两个砝码（也就是质量比它小的砝码中质量最大的两个）的质量的和．    约翰想知道，用他所拥有的这些砝码以及这架天平，能称出的质量最大是多少．由于天平的最大承重能力为C．他不能把所有砝码都放到天平上．</span></div>
<div><span style="font-size: medium">    现在约翰告诉你每个砝码的质量，以及天平能承受的最大质量．你的任务是选出一些砝码，</span></div>
<div><span style="font-size: medium">使它们的质量和在不压坏天平的前提下是所有组合中最大的．</span></div>
<div></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated positive integers, N and C. </span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Each line contains a single positive integer that is the mass of one weight. The masses are guaranteed to be in non-decreasing order. </span></p>
<div><span style="font-size: medium">    第1行：两个用空格隔开的正整数N和C.</span></div>
<p><span style="font-size: medium">    第2到N+1行：每一行仅包含一个正整数，即某个砝码的质量．保证这些砝码的质量是一个不下降序列</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer that is the largest mass that can be accurately and safely measured. </span></p>
<p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"> </span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">一个正整数，表示用所给的砝码能称出的不压坏天平的最大质量．</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 15//  三个物品,你的&#34;包包&#34;体积为15，下面再给出三个数字，从第三个数字开始，它都大于前面的二个数字之和，这个条件太重要<br/>
1<br/>
10<br/>
20<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
FJ has 3 weights, with masses of 1, 10, and 20 units. He can put at most 15<br/>
units on one side of his balance.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11 </span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">   </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">约翰有</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个砝码，质量分别为</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">10</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">20</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个单位．他的天平最多只能承受质量为</span><span lang="EN-US"><font face="Times New Roman">15</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个单位的物体．</span></span><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">用质量为</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">10</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的两个砝码可以称出质量为</span><span lang="EN-US"><font face="Times New Roman">11</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的牛．这</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个砝码所能组成的其他的质量不是</span></span><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">比</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">11</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">小就是会压坏天平</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

