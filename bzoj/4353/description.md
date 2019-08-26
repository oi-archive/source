
# Description

<div class="content"><div>给你一棵包含N个节点的树，设每条边一开始的边权为0，现在有两种操作：</div>
<div></div>
<div>1）给出参数U,V,C，表示把U与V之间的路径上的边权变成C（保证C≥0）</div>
<div></div>
<div>2）给出参数U,V,C，表示把U与V之间的路径上的边权加上C。但是如果U至V之间路径某条边的边权加上C小于0，那么C=这条边的边权的相反数。</div>
<div></div>
<div>你需要统计出每次一操作过后树中边权为0的边有多少条。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数N,M，分别表示表示节点个数与操作数。</div>
<div>接下来N-1行每行两个整数X,Y表示X,Y之间有一条边。</div>
<div>接下来M行每行4个整数P,U,V,C，P表示操作类型，U,V,C的意义见题目描述。</div>
<p></p></div>

# Output

<div class="content"><div>输出文件包括M行，每行一个整数，表示边权为0的边的个数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
1 4 5 1<br/>
2 5 3 1<br/>
2 5 1 -2<br/>
1 4 3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0<br/>
1<br/>
3</span></div>

# Hint

<div class="content"><p></p><div>N, M≤100,000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

