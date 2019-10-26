
# Description

<div class="content"><div>On a m*m land stationed n troops, numbered from 1 to n. The i-th troop&#39;s position can be described by two numbers (xi,yi) (1&lt;=xi&lt;=m,1&lt;=yi&lt;=m). It is possible that more than one troop stationed in the same place.</div>
<div>Then there are t minutes, in each minute one of the following two events will occur:</div>
<div>(1)the x-th troop moves towards a direction( Up(U) Down(D) Left(L) Right(R))for d units;(You can suppose that the troops won&#39;t move out of the boundary)</div>
<div>(2)the x-th troop needs to regroup the troops which stations in the same row or column with the x-th troop. That is, these troops need to move to the x-th troop&#39;s station.</div>
<div>Suggest the cost of i-th troop moving to the j-th troop is (xi-xj)^2+(yi-yj)^2, every time a troop regroups, you should output the cost of the regrouping modulo 10^9+7.</div>
<p></p></div>

# Input

<div class="content"><div>The first line: two numbers n,m(n&lt;=100000,m&lt;=10^18)</div>
<div>Next n lines each line contain two numbers xi,yi(1&lt;=xi,yi&lt;=m)</div>
<div>Next line contains a number t.(t&lt;=100000)</div>
<div>Next t lines, each line&#39;s format is one of the following two formats:</div>
<div>(1)S x d, S∈{U,L,D,R}, indicating the first event(1&lt;=x&lt;=n,0&lt;=d&lt;m)</div>
<div>(2)Q x, indicating the second event(1&lt;=x&lt;=n)</div>
<div>In order to force you to answer the questions online, each time you read x&#39;, x=x&#39;⊕lastans(&#34;⊕&#34; means &#34;xor&#34;), where lastans is the previous answer you output. At the beginning lastans=0. </div>
<p></p></div>

# Output

<div class="content"><div>
<div>Q lines, i-th line contain your answer to the i-th regrouping event.(modulo 10^9+7)</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 3<br/>
2 1<br/>
2 2<br/>
2 3<br/>
3 2<br/>
6<br/>
Q 1<br/>
L 0 2<br/>
L 5 2<br/>
Q 5<br/>
R 3 1<br/>
Q 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
7<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><div>The input after decode:</div><br/>
<div>Q 1</div><br/>
<div>L 1 2</div><br/>
<div>L 4 2</div><br/>
<div>Q 4</div><br/>
<div>R 2 1</div><br/>
<div>Q 2</div><br/>
<div><img src="/source/bzoj/3847/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMS9DNTAzLTEwMDgtMS5wbmc=.png" width="707" height="60" alt=""/></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

