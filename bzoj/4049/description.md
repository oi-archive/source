
# Description

<div class="content"><div>You travel through a scenic landscape consisting mostly of mountains - there are n landmarks(peaks a</div>
<div>nd valleys) on your path. You pause for breath and wonder: which mountain are voucurrently seeing on</div>
<div> the horizon?Formally: you are given a polygonal chain PIP2 - Pn in the plane. The x coordinates of </div>
<div>thepoints are in strictly increasing order. For each segment PiPi+l of this chain, find the smallest</div>
<div>index j &gt; i, for which any point of PjPj+i is visible from PiPi+l (lies strictly above the ravPiPi~+</div>
<div>l ) .</div>
<div>给定一个折线图，按x轴递增的顺序给出。对于每个条line，求出在它之后，且下标最小的line。输出这个下标。 </div>
<div>n&lt;=100000</div>
<div></div>
<div></div>
<div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div><span style="font-size: 11.8181819915771px;">The first line of input contains the number of test cases T. The descriptions of the test cases </span></div>
<div>
<div style="font-size: 11.8181819915771px;">follow: </div>
<div style="font-size: 11.8181819915771px;">The first line of each test case contains an integer &#39;n (2&lt; = N &lt; 100000) - the number ofvertices on</div>
<div style="font-size: 11.8181819915771px;">the chain.Each of the following n lines contains integer coordinates xi, Yi of the vertex Pi (0 &lt; xi</div>
<div style="font-size: 11.8181819915771px;"> &lt;X2 &lt; ... &lt; Xn≤ 109; 0 &lt; Yi &lt; 10^9).</div>
<div style="font-size: 11.8181819915771px;"></div>
</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">For each test case, output a single line contaimng n - I space-separated integers. These shouldbe th</div>
<div style="font-size: 11.8181819915771px;">e smallest indices of chain segments visible to the right, or o when no such segment exists.Problem </div>
<div style="font-size: 11.8181819915771px;">B: Mountainous landscape</div>
<div></div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
8<br/>
0 0<br/>
3 7<br/>
6 2<br/>
9 4<br/>
11 2<br/>
13 3<br/>
17 13<br/>
20 7<br/>
7<br/>
0 2<br/>
1 2<br/>
3 1<br/>
4 0<br/>
5 2<br/>
6 1<br/>
7 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 3 6 5 6 0 0<br/>
6 4 4 0 6 0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

