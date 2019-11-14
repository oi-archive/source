
# Description

<div class="content"><div>
<div>这个问题是源于一个在棋盘上玩的，由Sid Sackson设计的名叫Can&#39;t stop的游戏的。这个问题与Can&#39;t stop有一定的相似之处，但是不需要玩过Can&#39;t stop。</div>
<div>你在玩一个（非常大型的）棋盘游戏。在这个游戏里面，给出了一个长度为N的roll set的序列。每个roll set包括D个die roll，每个die roll是一个正整数。</div>
<div>你需要找到序列中总长度最大的极好的区间。区间即为连续的一段roll set。如果存在k个数使某个区间内的所有roll set都至少包含其中一个，那么，这个区间就被认为是极好的。</div>
<div>例如：d=2，k=3时，roll set如下：</div>
<div></div>
<div>Set 0: 10 20</div>
<div>Set 1: 50 60</div>
<div>Set 2: 70 30</div>
<div>Set 3: 40 40</div>
<div>Set 4: 30 30</div>
<div>Set 5: 20 40</div>
<div>从0到2的区间是极好的，因为从0到2中的每个roll set都包含了10,50或70 。从1到5的区间也是极好的，因为1到5的所有roll set都包含50,30或40。它包含了5个roll set，是总长度最大的极好的区间。</div>
<div>你的任务是输出总长度最大的极好的区间的第一个元素的下标和最后一个元素的下标。如果有多个长度一样的，输出第一个元素下标最小的。请注意下标从0开始。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数T，表示数据组数。接下来T组数据。</div>
<div>每组数据的第一行是三个正整数N,D,k，描述如上。接下来一行，包含N*D个整数，前D个整数表示第一个roll set ，接下来D个表示第二个roll set，以此类推。</div>
<p></p></div>

# Output

<div class="content"><div>对于每个case，输出一行，&#34;Case #x: y z&#34;，x表示case标号（从1开始），y和z是答案区间的第一个和最后一个元素的下标。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
8 1 2<br/>
1 2 3 2 4 5 4 6<br/>
4 3 2<br/>
1 2 3 4 5 6 7 8 9 10 11 12<br/>
6 2 3<br/>
10 20 50 60 70 30 40 40 30 30 20 40<br/>
10 1 3<br/>
2 4 3 1 4 5 3 1 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 1 3<br/>
Case #2: 0 1<br/>
Case #3: 1 5<br/>
Case #4: 1 4<br/>
</span></div>

# Hint

<div class="content"><p></p><div>【数据范围】</div><br/>
<div>对于45%的数据，N&lt;=1000</div><br/>
<div>对于50%的数据，k=2</div><br/>
<div>前两部分数据共计70%</div><br/>
<div>对于100%的数据，2&lt;=k&lt;=3</div><br/>
<div>输入文件在4.8M以内</div><br/>
<div>T=10.</div><br/>
<div>1 ≤ D ≤ 4.</div><br/>
<div>1 ≤ 每个die roll ≤ 10^5.</div><br/>
<div>对于最多6个case, 1 ≤ N ≤ 10^5.</div><br/>
<div>对于其他所有的case, 1 ≤ N ≤ 10^3.</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

