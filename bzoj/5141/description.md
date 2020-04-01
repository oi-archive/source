
# Description

<div class="content"><div>
<div>Farmer John has a large farm with N barns (1≤N≤10^5), some of which are already painted and some n</div>
<div>ot yet painted. Farmer John wants to paint these remaining barns so that all the barns are painted, </div>
<div>but he only has three paint colors available. Moreover, his prize cow Bessie becomes confused if two</div>
<div> barns that are directly reachable from one another are the same color, so he wants to make sure thi</div>
<div>s situation does not happen.It is guaranteed that the connections between the N barns do not form an</div>
<div>y &#39;cycles&#39;. That is, between any two barns, there is at most one sequence of connections that will l</div>
<div>ead from one to the other.How many ways can Farmer John paint the remaining yet-uncolored barns?</div>
<div>给你一颗大小为n&lt;=1e5的树，三种颜色，每个点涂一种颜色，相邻点不能同色。下面告诉你一些点已经被涂色，并</div>
<div>且告诉你是哪一种颜色，问你涂完整棵树有多少种方法?mod 1e9+7。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line contains two integers N and K (0≤K≤N), respectively the number of barns on the farm </div>
<div>and the number of barns that have already been painted.</div>
<div>The next N-1lines each contain two integers xx and yy (1≤x,y≤N,x≠y) describing a path directly connecting barns x and y.</div>
<div>The next K lines each contain two integers bb and cc (1≤b≤N, 1≤c≤3) indicating that barn bb is painted with color c.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Compute the number of valid ways to paint the remaining barns, modulo 10^9+7, </div>
<div>such that no two barns which are directly connected are the same color.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
1 2<br/>
1 3<br/>
1 4<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

