
# Description

<div class="content"><p></p>
<div>WelcometoSAO(StrangeandAbnormalOnline)。这是一个VRMMORPG，含有n个关卡。但是，挑战不同关卡的顺序是一</div>
<div>个很大的问题。有n–1个对于挑战关卡的限制，诸如第i个关卡必须在第j个关卡前挑战，或者完成了第k个关卡才</div>
<div>能挑战第l个关卡。并且，如果不考虑限制的方向性，那么在这n–1个限制的情况下，任何两个关卡都存在某种程</div>
<div>度的关联性。即，我们不能把所有关卡分成两个非空且不相交的子集，使得这两个子集之间没有任何限制。</div></div>

# Input

<div class="content"><div>第一行，一个整数T，表示数据组数。对于每组数据，第一行一个整数n，表示关卡数。接下来n–1行，每行为“i </div>
<div>sign j”，其中0≤i,j≤n–1且i≠j，sign为“&lt;”或者“&gt;”，表示第i个关卡必须在第j个关卡前/后完成。</div>
<div>T≤5，1≤n≤1000</div></div>

# Output

<div class="content"><p>对于每个数据，输出一行一个整数，为攻克关卡的顺序方案个数，mod1,000,000,007输出。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
10<br/>
5 &gt; 8<br/>
5 &gt; 6<br/>
0 &lt; 1<br/>
9 &lt; 4<br/>
2 &gt; 5<br/>
5 &lt; 9<br/>
8 &lt; 1<br/>
9 &gt; 3<br/>
1 &lt; 7<br/>
10<br/>
6 &gt; 7<br/>
2 &gt; 0<br/>
9 &lt; 0<br/>
5 &gt; 9<br/>
7 &gt; 0<br/>
0 &gt; 3<br/>
7 &lt; 8<br/>
1 &lt; 2<br/>
0 &lt; 4<br/>
10<br/>
2 &lt; 0<br/>
1 &gt; 4<br/>
0 &gt; 5<br/>
9 &lt; 0<br/>
9 &gt; 3<br/>
1 &lt; 2<br/>
4 &gt; 6<br/>
9 &lt; 8<br/>
7 &gt; 1<br/>
10<br/>
0 &gt; 9<br/>
5 &gt; 6<br/>
3 &gt; 6<br/>
8 &lt; 7<br/>
8 &gt; 4<br/>
0 &gt; 6<br/>
8 &gt; 5<br/>
8 &lt; 2<br/>
1 &gt; 8<br/>
10<br/>
8 &lt; 3<br/>
8 &lt; 4<br/>
1 &gt; 3<br/>
1 &lt; 9<br/>
3 &lt; 7<br/>
2 &lt; 8<br/>
5 &gt; 2<br/>
5 &lt; 6<br/>
0 &lt; 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">2580<br/>
3960<br/>
1834<br/>
5208<br/>
3336</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

