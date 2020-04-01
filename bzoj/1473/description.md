
# Description

<div class="content">CS是一个十分狭长的国家，即使这个国家已经十分现代化了，但是人们却总喜欢用书信的方式来与人交流，所以CS长期以来糟糕的邮政机构，一直在遭受这人们的抨击。
现在，老boss：CmdButtons上台了，作为他竞选演说中的首要任务，他决定改善CS的邮政机构。CS一共有n个城市，分布在狭长的国土上。CmdButtons决定在其中修建一些邮局，使得每个城市的信件都投放到距离它最近的邮局中去。但是，我们都知道，CmdButtons比较吝啬（当然是建立在CS薄弱的财政上的），把一封信运送一公里是需要一定资金的，同时建立邮局也是需要一定资金的。CmdButtons想要找到一种方案（至少建立一所邮局），使得CS的投资最少。
使问题更加明确，我们认为CS建立在一个数轴上，城市从负方向向正方向按照1至n标号，d[i]表示城市i离原点的距离并且d[1] = 0，对于I &lt;&gt; j有d[i] &lt;&gt; d[j]。城市i里的居民人数为w[i]，如果每个居民的信件需要投放到dis以外的邮局去，那么未来几年内政府为了该城市的居民投放信件将总花费w[i] * dis的资金。另外，在城市i建立邮局的费用为c[i]。
找出一种方案，使得CmdButtons在未来几年内的总花费最小（否则他会扣你的工资）。

   
</div>

# Input

<div class="content">第一行一个正整数n（n &lt;= 1500）；
第二行n个正整数d[1..n]（保证递增，不大于10000）；
第三行n个正整数c[1..n]（不大于10000）；
第四行n个正整数w[1..n]（不大于10000）；

</div>

# Output

<div class="content">只有一行，即为CmdButtons在未来几年内的最小总花费。
</div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
0 378 2508 5061 5100 6143 7929 8243 8719 8872 <br/>
268 649296 345844 560431 980759 147303 434065 335042 547607 917275 <br/>
165 6387 9826 6095 6170 6582 3066 4688 2831 8274 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4063297<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

