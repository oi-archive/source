
# Description

<div class="content"><div>Farmer John has recently been experimenting with cultivating different types of grass on his farm, r</div>
<div>ealizing that different types of cows like different types of grass. However, he must be careful to </div>
<div>ensure that different types of grass are planted sufficiently far away from each-other, in order to </div>
<div>prevent them from being inextricably mixed.FJ&#39;s farm consists of Nfields (1≤N≤200,000), where M pa</div>
<div>irs of fields are connected by bi-directional pathways (1≤M≤200,000). Using these pathways, it is </div>
<div>possible to walk from any field to any other field. Each pathway has an integer length in the range </div>
<div>1…1,000,000. Any pair of fields will be linked by at most one direct pathway.In each field, FJ init</div>
<div>ially plants one of Ktypes of grass (1≤K≤N). Over time, however, he might decide to switch the gra</div>
<div>ss in some field to a different type. He calls this an &#34;update&#34; operation. He might perform several </div>
<div>updates over the course of time, which are all cumulative in nature.After each update, FJ would like</div>
<div> to know the length of the shortest path between two fields having different grass types. That is, a</div>
<div>mong all pairs of fields having different grass types, he wants to know which two are closest. Ideal</div>
<div>ly, this number is large, so he can prevent grass of one type from mixing with grass of another type</div>
<div>. It is guaranteed that the farm will always have at least two fields with different grass types.In </div>
<div>30 percent of the input cases, each field will be directly connected to at most 10 pathways.</div>
<div>
<div>给定一张带权无向图，每个点有一个颜色，每次改变一个点的颜色，要求你在操作后输出这个图中最近异色点对之</div>
<div>间的距离最近异色点对定义为：一对点颜色不同，且距离最小</div>
</div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains four integers, N, M, K, and Q, where Q is the number of updates (1</div>
<div>≤Q≤200,000). The next M lines describe the paths; each one contains three integers A, B, and L, in</div>
<div>dicating a path from field A to field B (both integers in the range 1…N) of length L. The next line</div>
<div> indicates the initial type of grass growing in each field (N integers in the range 1…K). Finally, </div>
<div>the last Q lines each describe an update, specified by two integers A and B, where the grass in fiel</div>
<div>d A is to be updated to type B</div>
<p></p></div>

# Output

<div class="content"><div>For each update, print the length of the shortest path between two fields with different types of grass</div>
<div>
<div>after the update is applied.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 3 4<br/>
1 2 3<br/>
2 3 1<br/>
1 1 2<br/>
3 3<br/>
2 3<br/>
1 2<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
3<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

