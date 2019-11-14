
# Description

<div class="content"> 给定一个长度为n的序列C1, C2…Cn，我们称C的单调序列就是把它改成一个严格单调递增的序列D1,D2..Dn(D1<d2<..<dn)或者是严格递减的序列d1,d2..dn(d1>D2&gt;..&gt;Dn)，同时我们定义它的代价就是|D1-C1|+|D2-C2|…|Dn-Cn|．
这个问题你是不是看得非常眼熟呢? 
下面请考虑这个问题的加强版把．
请你把这个长度为n的序列分成m段，其中要求将每段改成一个单调序列，同时要求代价和最小．比如说1,2,3,2,1就是一个满足要求2段单调序列(1,2,3),(2,1)，而将1,1,1,1改成2段单调序列的最优的方案就是(1,2),(2,1)，它的代价就是2．
</d2<..<dn)或者是严格递减的序列d1,d2..dn(d1></div>

# Input

<div class="content">第1行2个数n, m．
接下来n行，每行一个数，按顺序给出C1, C2…Cn．
</div>

# Output

<div class="content">一个数，即最小的代价和．
</div>

# Sample Input

<div class="content"><span class="sampledata">6 1<br/>
1<br/>
2<br/>
3<br/>
3<br/>
2<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
</span></div>

# Hint

<div class="content"><p>30%的数据,  n&lt;=100．<br/>
20%的数据,  m=1．<br/>
100%的数据，n&lt;=2000, m&lt;=min{n,10}，Ci&lt;=10000．<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

