
# Description

<div class="content"><p>P 工厂是一个生产纸箱的工厂。纸箱生产线在人工输入三个参数 n p a , , 之后，<br/>
即可自动化生产三边边长为</p>
<p>(a mod P,a^2 mod p,a^3 mod P)<br/>
(a^4 mod p,a^5 mod p,a^6 mod P)<br/>
....<br/>
(a^(3n-2) mod p,a^(3n-1) mod p,a^(3n) mod p)</p>
<p>的n个纸箱。在运输这些纸箱时，为了节约空间，必须将它们嵌套堆叠起来。<br/>
一个纸箱可以嵌套堆叠进另一个纸箱当且仅当它的最短边、次短边和最长边<br/>
长度分别严格小于另一个纸箱的最短边、次短边和最长边长度。这里不考虑<br/>
任何旋转后在对角线方向的嵌套堆叠。 <br/>
你的任务是找出这n个纸箱中数量最多的一个子集，使得它们两两之间都可<br/>
嵌套堆叠起来。</p></div>

# Input

<div class="content"><p>输入文件的第一行三个整数，分别代表 a,p,n  <br/>
</p></div>

# Output

<div class="content"><p> <br/>
输出文件仅包含一个整数，代表数量最多的可嵌套堆叠起来的纸箱的个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata"> 10 17 4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
2 <br/>
【样例说明】 <br/>
生产出的纸箱的三边长为(10, 15, 14), (4, 6, 9) , (5, 16, 7), (2, 3, 13)。其中只有<br/>
(4, 6, 9)可堆叠进(5, 16, 7)，故答案为 2。<br/>
2&lt;=P&lt;=2000000000,1&lt;=a&lt;=p-1,a^k mod p&lt;&gt;0,ap&lt;=2000000000,1&lt;=N&lt;=50000 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

