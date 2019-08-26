
# Description

<div class="content"><p><span style="font-size: medium">Wayne喜欢看书，更喜欢买书。<br/>
某天Wayne在当当网上买书，买了很多很多书。Wayne有一个奇怪的癖好，就是第一本书的价格必须恰为X，而之后买的每一本书，若是比上一本更昂贵，则价格最多多A元；若是比上一本更便宜，则价格最多少B元。<br/>
Wayne心血来潮，一口气买了N本书，但他记不得每本书的价格了，只记得总价格是M。Wayne于是很想知道一种可能的书价分布。为了简化问题，我们假定书价的定义域是整数，且每本书与上一本书的价格差，要么恰为+A，要么恰为-B。<br/>
只要给出任意一个合法的书价序列就算正确。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行一个正整数N。<br/>
第二行四个整数依次是X,A,B,M。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出一行N个整数，用空格隔开。数据保证有解。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
10 1 2 37<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10 11 9 7<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据规模和约定】<br/><br/>
对于5%的数据，满足N = 1。<br/><br/>
对于另外25%的数据，满足A = B = 1, N &lt;= 100。<br/><br/>
对于另外10%的数据，满足A, B &lt;= 5, N &lt;= 100。<br/><br/>
对于另外20%的数据，满足N &lt;= 1000。<br/><br/>
对于100%的数据，满足1 &lt;= A, B &lt;= 10^6，|X| &lt;= 10^6，N &lt;= 10^5，M可用带符号64位整型存储。 <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=zcwwzdjn提供">zcwwzdjn提供</a></p></div>

