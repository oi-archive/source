
# Description

<div class="content"><div>分曹射覆蜡灯红，膜拜神犇lzr；</div>
<div>渚清沙白鸟飞回，长跪巨神ljw。</div>
<div>lzr就是被称为hack狂魔的qmqmqm，相比很多人都已经知道了。</div>
<div>ljw虽然没有lzr有名，但是在cf、bc等比赛里的hack次数也是数一数二的。</div>
<div>SD的这两位神犇今天决定进行一场hack比赛。</div>
<div>经过研究，他们决定hack SD的另一位神犇jzh做过的题。</div>
<div>我们设jzh已经做过了n道题。这些题目因为知识点之间的联系而形成了一棵树结构。1号题目(A+B problem)是这棵树的根。</div>
<div>因为slyz也不乏hack高手，所以jzh做的这n道题有些已经被hack了。</div>
<div>现在ljw先手，两人轮流操作。一次操作为：选择一道没有被hack过的题x，然后将x到1的路径上的所有没有被hack过的题全部hack掉。</div>
<div>无法操作者输。</div>
<div>我们假设ljw和lzr的智商都是无比的高(事实也是如此)，都会采取对自己最有利的操作。</div>
<div>ljw当然想赢下这场比赛了！于是他想算一下最终他能否赢下比赛。如果他能赢，他还想知道在保证他赢的情况下第一步他选择哪些题。</div>
<div>这么简单的问题ljw神犇当然会了。不过他想考考你。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数n(n&lt;=100000)，代表jzh神犇做过的题数。</div>
<div>第二行n个整数，每个整数为0或1。其中第i个数为0代表第i道题还没有被hack，第i个数为1代表第i道题已经被slyz的神犇hack了。</div>
<div>接下来n-1行描述jzh做过的题目形成的树。每行两个整数u,v代表第u道题和第v道题之间有一条边。</div>
<p></p></div>

# Output

<div class="content"><div>如果ljw不能赢得比赛，那么输出-1。</div>
<div>否则升序输出所有题号x。x满足ljw在保证赢的情况下第一步可以选择x。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
1 1 0 1 0 0 1 0<br/>
1 2<br/>
1 3<br/>
2 6<br/>
3 4<br/>
3 5<br/>
5 7<br/>
7 8 </span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据范围：1&lt;=u,v&lt;=n&lt;=100000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

