
# Description

<div class="content"><div><span style="font-size: medium">一个无向图，N个点，编号从1~N，M条边，编号从1~M。接下来Q个操作，插入一条边，编号为原有编号数+1；删除一条边，编号数不变；询问两个点是否能够互达。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行两个整数N,M</span></div>
<div><span style="font-size: medium">接下来M行，每行两个整数，表示该条边所连接的两个点。</span></div>
<div><span style="font-size: medium">接下来一行一个整数Q</span></div>
<div><span style="font-size: medium">接下来Q行，是以下三种之一:</span></div>
<div><span style="font-size: medium">D x，表示删除编号为x的边（一条边被删除多次等价于删除一次）</span></div>
<div><span style="font-size: medium">I x y，表示在点x和点y之间插入一条边</span></div>
<div><span style="font-size: medium">Q x y，表示询问点x和点y是否能互达</span></div>
<div><span style="font-size: medium">保证点和边的编号合法。</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">对于每个询问输出一行，”Yes”表示能达到，”No”表示不能。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
1 2<br/>
5<br/>
Q 1 2<br/>
D 1<br/>
Q 1 2<br/>
I 1 2<br/>
Q 1 2<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
Yes<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
对于100%的数据，N&lt;=50000,M&lt;=100000,Q&lt;=100000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

