
# Description

<div class="content"><div>After solves all problem of the series COT(count on a tree), ZCC feels bored and came up with a new COT problem, where letter T stands of Tetrahedron.</div>
<div>In this problem, Tetrahedron is define as a set of point:</div>
<div>T(n) = {(x, y, z) | 1≤z≤y≤x≤n}</div>
<div>Imagine T(n) is divided into n layers, the k-th layer contains k rows, of which the l-th row contains l points.</div>
<div>Moreover, we define sub-Tetrahedron a set of point, too:</div>
<div>sT(x, y, z, a) = {(x+i, y+j, z+k) | 0≤k≤j≤i＜a}</div>
<div>First of all, you are given a Tetrahedron T(N), every point of T(N) has a value of 0.</div>
<div>Then, you should deal with M operation (Mxi, Myi, Mzi, Mai), means you should add 1 to every point’s value if it belongs to sT(Mxi, Myi, Mzi, Mai).</div>
<div>Then, you should deal with Q queries (Qxi, Qyi, Qzi, Qai), you should output the sum of values of points in sT(Qxi, Qyi, Qzi, Qai).</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>First line: three positive integer N, M, Q.(N≤100, M≤100000, Q≤100000)</div>
<div>Then followed M lines, each line contains four integers Mxi, Myi, Mzi, Mai, which describe an operation.</div>
<div>Then followed Q lines, each line contains four integers Qxi, Qyi, Qzi, Qai, which describe a query.</div>
<p></p></div>

# Output

<div class="content"><div>For every query, output a line with one integer, the answer to the query. </div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 2<br/>
1 1 1 2<br/>
1 1 1 2<br/>
2 1 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1</span></div>

# Hint

<div class="content"><p></p><div>It is guaranteed, for every sT(x, y, z, a): 1≤z≤y≤x≤x+a-1≤N. </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

