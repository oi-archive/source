
# Description

<div class="content"><div>
<div>有n个星球，它们的编号是1到n，它们坐落在同一个星系内，这个星系可以抽象为一条数轴，每个星球都是数轴上的一个点，</div>
<div>特别地，编号为i的星球的坐标是i。</div>
<div>一开始，由于科技上的原因，这n个星球的居民之间无法进行交流，因此他们也不知道彼此的存在。</div>
<div>现在，这些星球独立发展出了星际穿越与星际交流的工具。</div>
<div>对于第i个星球，他通过发射强力信号，成功地与编号在[Li,i-1]的所有星球取得了联系(编号为1的星球没有发出任何信号)，</div>
<div>取得联系的两个星球会建立双向的传送门，对于建立了传送门的两个星球u,v，u上的居民可以花费1单位时间传送到v，</div>
<div>v上的居民也可以花费1单位时间传送到u，我们用dist(x,y)表示从编号为x的星球出发，通过一系列星球间的传送门，</div>
<div>传送到编号为y的星球最少需要花费的时间。</div>
<div>现在有q个星际商人，第i个商人初始所在的位置是xi,他的目的地是[Li,Ri]中的其中一个星球，保证Li&lt;Ri&lt;xi。</div>
<div>他会在这些星球中等概率挑选一个星球y(每个星球都有一样的概率被选中作为目的地)，</div>
<div>然后通过一系列星球的传送门，花费最少的时间到达星球y。</div>
<div>商人想知道他花费的期望时间是多少？也就是计算∑dist(xi,y)/(Ri-Li+1),其中y&lt;=Li&lt;=Ri</div>
</div>
<div></div></div>

# Input

<div class="content"><div>第一行一个正整数n，表示星球的个数。</div>
<div>第二行n-1个正整数，第i个正整数为Li+1，</div>
<div>表示编号在[Li+1,i]区间内所有星球已经与编号为i+1的星球取得了联系，并且可以通过花费1单位进行彼此的传输。保证Li+1≤i</div>
<div>第三行一个正整数q，表示询问组数。</div>
<div>接下来q行，每行三个数字Li,Ri,xi，表示在[Li,Ri]这个区间中等概率选择一个星球y，dist(xi,y)的期望。</div>
<div>保证Li&lt;Ri&lt;xi,n,q≤3×10^5</div>
<div></div></div>

# Output

<div class="content"><div>对于每组询问，注意到答案必然是一个有理数，因此以p/q的格式输出这个有理数，要求gcd(p,q)=1</div>
<div>如果答案为整数m，输出m/1</div>
<div></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 1 2 1 4 6<br/>
5<br/>
3 4 6<br/>
1 5 7<br/>
1 2 4<br/>
1 2 6<br/>
1 3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3/2<br/>
13/5<br/>
3/2<br/>
2/1<br/>
1/1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

