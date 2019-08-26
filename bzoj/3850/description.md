
# Description

<div class="content"><div>Though ZCC has many Fans, ZCC himself is a crazy Fan of a coder, called &#34;Memset137&#34;.</div>
<div>It was on Codefires(CF), an online competitive programming site, that ZCC knew Memset137, and immediately became his fan.</div>
<div>But why?</div>
<div>Because Memset137 can solve all problem in rounds, without unsuccessful submissions; his estimation of time to solve certain problem is so accurate, that he can surely get an Accepted the second he has predicted. He soon became IGM, the best title of Codefires. Besides, he is famous for his coding speed and the achievement in the field of Data Structures.</div>
<div>After become IGM, Memset137 has a new goal: He wants his score in CF rounds to be as large as possible.</div>
<div>What is score? In Codefires, every problem has 2 attributes, let&#39;s call them Ki and Bi(Ki, Bi＞0). if Memset137 solves the problem at Ti-th second, he gained Bi-Ki*Ti score. It&#39;s guaranteed Bi-Ki*Ti is always positive during the round time.</div>
<div>Now that Memset137 can solve every problem, in this problem, Bi is of no concern. Please write a program to calculate the minimal score he will lose.(that is, the sum of Ki*Ti).</div>
<p></p></div>

# Input

<div class="content"><div>The first line contains an integer N(1≤N≤10^5), the number of problem in the round.</div>
<div>The second line contains N integers Ei(1≤Ei≤10^4), the time(second) to solve the i-th problem.</div>
<div>The last line contains N integers Ki(1≤Ki≤10^4), as was described.<span class="Apple-tab-span" style="white-space:pre">	</span></div>
<div>有n个项目，第一行有n个数字，第i个数字为第i个物品的损失度，</div>
<div>第二行有i个数字，</div>
<div>第i个数字为第i个物品的耗时，每一个物品的消耗为当前已经做了的（包括当前项）的总时间*（当前物品的）损失度。</div>
<div>请你安排顺序，使总消耗最小。</div></div>

# Output

<div class="content"><div>One integer L, the minimal score he will lose.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
10 10 20<br/>
1 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">150</span></div>

# Hint

<div class="content"><p></p><div>Memset137 takes the first 10 seconds to solve problem B, then solves problem C at the end of the 30th second. Memset137 gets AK at the end of the 40th second.</div><br/>
<div>L = 10 * 2 + (10+20) * 3 + (10+20+10) * 1 = 150. </div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

