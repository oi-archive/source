
# Description

<div class="content"><p>JYY和CX的结婚纪念日即将到来，JYY来到萌萌开的礼品店选购纪念礼物。<br/>
萌萌的礼品店很神奇，所有出售的礼物都按照特定的顺序都排成一列，而且相邻<br/>
的礼物之间有一种神秘的美感。于是，JYY决定从中挑选连续的一些礼物，但究<br/>
竟选哪些呢？<br/>
【问题描述】<br/>
假设礼品店一共有N件礼物排成一列，每件礼物都有它的美观度。排在第i<br/>
1&lt; =i&lt; =N个位置的礼物美观度为正整数Ai,。JYY决定选出其中连续的一段，<br/>
即编号为礼物i,i+1,…,j-1,j的礼物。选出这些礼物的美观程度定义为<br/>
(M（i,j)-m(i,j))/(j-i+k)<br/>
其中M(i,j)表示max{Ai,Ai+1....Aj}，m(i,j)表示min{Ai,Ai+1....Aj}，K为给定的正整数。<br/>
由于不能显得太小气，所以JYY所选礼物的件数最少为L件；同时，选得太<br/>
多也不好拿，因此礼物最多选R件。JYY应该如何选择，才能得到最大的美观程<br/>
度？由于礼物实在太多挑花眼，JYY打算把这个问题交给会编程的你。</p></div>

# Input

<div class="content"><p>本题每个测试点有多组数据。输入第一行包含一个正整数T(T&lt; =10)，表示<br/>
有T组数据。<br/>
每组数据包含两行，第一行四个非负整数N,K,L,R(2&lt; =L&lt; =R&lt; =N。第二行<br/>
包含N个正整数，依次表示A1,A2....An,(Ai&lt; =10^8),N,K&lt; = 50,000</p></div>

# Output

<div class="content"><p>输出T行，每行一个非负实数，依次对应每组数据的答案，数据保证答案不<br/>
会超过10^3。输出四舍五入保留4位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5 1 2 4<br/>
1 2 3 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.7500 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

