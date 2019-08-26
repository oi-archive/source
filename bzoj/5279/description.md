
# Description

<div class="content"><div>Farmer John自豪于他所经营的交通发达的的农场。这个农场是由N块牧场（2≤N≤50,000）组成的，N?1条双向道</div>
<div>路将它们连接起来，每一条道路的都为一单位长度。Farmer John注意到，从任何一块牧场到另一块牧场，都能通</div>
<div>过一组合适的道路到达。尽管FJ的农场现在是连通的，他担心如果有一条道路被阻断会发生什么，因为这事实上会</div>
<div>将他的农场分为两个不相交的牧场集合，奶牛们只能够在每一个集合内移动但不能在集合间移动。于是FJ又建造了</div>
<div>M条额外的双向道路（1≤M≤50,000），每一条的长度都是一个至多为10^9的正整数。奶牛们仍然可以使用原有的</div>
<div>道路进行移动，除非其中的某些被阻断了。如果某条原有的道路被阻断了，农场就会被分为两块不相交的区域，那</div>
<div>么FJ就会从他的额外修建的道路中选择一条能够重建这两块区域的连通性的，取代原来那条，从而奶牛们又可以从</div>
<div>任何一块牧场去往另一块牧场。对于农场上每一条原有的道路，帮助FJ选出最短的替代用的道路。</div></div>

# Input

<div class="content"><div>输入的第一行包含N和M。接下来的N-1行，每行用整数p和q描述了一条原有的道路</div>
<div>其中p≠q是这条道路连接的两块牧场（在1…N范围内）。</div>
<div>剩下的M行，每行用三个整数p、q和r描述了一条额外的道路，其中r是这条道路的长度。</div>
<div>任何两块牧场之间至多只有一条道路。</div></div>

# Output

<div class="content"><div>对原有的N-1条道路的每一条，按照它们在输入中出现的顺序</div>
<div>输出如果这条道路被阻断的话，能够重新连接农场的最短的替代用道路的长度。</div>
<div>如果不存在合适的替代用的道路，输出-1。</div></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 2<br/>
1 3<br/>
4 1<br/>
4 5<br/>
6 5<br/>
2 3 7<br/>
3 6 8<br/>
6 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
7<br/>
8<br/>
5<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

