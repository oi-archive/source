
# Description

<div class="content"><p> 与当地鞋匠协会发生冲突的瓦维尔城堡的龙决定将它的狩猎场移出克拉科夫以减少敌对的邻居数量。现在他正在给和平而宁静的Bytes王国带来灾难与恐怖。</p>
<div>在Bytes王国有n条河流，每一条河流都是一条直线（你可以认为Bytes王国就像是欧几里得平面上被一些直线划分的一些区域），不存在三条河流共用同一个点，河流们将王国划分成了一些区域。</div>
<div>幸运的是，现在王国里有m个勇士。每个勇士都发誓要保护其所在的区域。王国也许就因此受到了长远持久的保护？</div>
<div>我们所知道的只有龙不会攻击存在至少一个勇士的区域。勇士们因为他们的勇气被人所熟知，然而他们的智力却低的可怕，他们不会离开自己所在的区域，只会保护所在的区域。</div>
<div>给出一个王国的地图，和勇士的坐标，请你计算是否所有的区域都被保护到了。</div>
<div></div></div>

# Input

<div class="content"><p>第一行一个正整数T，表示有T组数据。</p>
<div>
<div>每组数据第一行两个正整数n和m，表示有n条河流，m个勇士，1 &lt;= n &lt;= 100, 1 &lt;= m &lt;= 50000。</div>
<div>接下来n行，第j行三个整数A_j, B_j, C_j，表示第j个河流的直线方程是A_j * x + B_j * y + C_j = 0，三个数字的绝对值都不超过10000。</div>
<div>接下来m行，第i行两个整数X_i, Y_i，表示第i个勇士的坐标是(X_i, Y_i)，-10^9 &lt;= X_i, Y_i &lt;= 10^9。</div>
<div>你可以认为没有一个勇士站在河流上（如果他这么做他的铠甲会很快生锈呢）。两个勇士的坐标可能相同。不存在两条河流是重合的直线，不存在三条河流共用同一个点。</div>
<div></div>
<div></div>
</div></div>

# Output

<div class="content"><p>对于每组数据输出一行，如果每个区域都可以被保护，输出&#34;PROTECTED&#34;，否则输出&#34;VULNERABLE&#34;。（不含引号）</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 7<br/>
0 1 0<br/>
1 0 0<br/>
1 1 -3<br/>
1 1<br/>
5 -1<br/>
3 2<br/>
2 -2<br/>
-2 6<br/>
-1 -2<br/>
-8 4<br/>
1 1<br/>
0 1 0<br/>
0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">PROTECTED<br/>
VULNERABLE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

