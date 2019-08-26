
# Description

<div class="content"><div>In The City of Eternal Festivities, there are n street junctions and n - I bidirectional streets,eac</div>
<div>h street connecting two of the junctions. Between every two junctions, there is exactly one(direct o</div>
<div>r indirect) path connecting them. No junction is an endpoint for more than 10 streets.Every 13th of </div>
<div>September (the 256th day of the year), there are many festivities going on inThe City. In particular</div>
<div>, the citizens want to organize m parades. The parade number 7; starts atjunction ui and ends at vi,</div>
<div> following the unique path between the endpoints.As the mayor of The City, you are responsible for c</div>
<div>itizens&#39; safety. Therefore you decreed thatno two parades are ever allowed to use the same street, t</div>
<div>hough they can have common junctions,or even common endpoints.To appease your citizens, try to organ</div>
<div>ize as many parades as possible, without breaking thesafety regulations.</div>
<div>一个树，d(v)&lt;=10，给定m条path，找出最多不共边的path，不需要方案。 </div>
<div>n&lt;=1000,m&lt;=总路径数</div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">The first line of input contains the number of test cases T. The descriptions of the test cases </div>
<div style="font-size: 11.8181819915771px;">follow: </div>
<div style="font-size: 11.8181819915771px;">The first line of each test case contains a single integer: the number of junctions n (2《 n≤1000).</div>
<div style="font-size: 11.8181819915771px;"> Each of the next n - I lines contains two integers a, b (1《 a≠ b≤ n), denoting thatjunctions a a</div>
<div style="font-size: 11.8181819915771px;">nd b are connected by a street. Each junction has at most 10 streets leaving it.The next line contai</div>
<div style="font-size: 11.8181819915771px;">ns a single integer: the number of planned parades m, 0≤ m &lt;(彩.Each of the next m lines contains t</div>
<div style="font-size: 11.8181819915771px;">wo integers ui, vi (1≤ ui≠ vi≤n), meaning that a parade isplanned to start at junction ui, and fi</div>
<div style="font-size: 11.8181819915771px;">nish at junction vi. No two parades share both endpoints.</div>
<div style="font-size: 11.8181819915771px;"></div>
<div></div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">For each test case, output one line containing the largest number of parades that can beorganized wi</div>
<div style="font-size: 11.8181819915771px;">th no street used bv more than one parade.</div>
<div style="font-size: 11.8181819915771px;"></div>
<div></div>
<div>
<div></div>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
6<br/>
1 2<br/>
2 3<br/>
3 4<br/>
3 5<br/>
3 6<br/>
4<br/>
1 3<br/>
4 5<br/>
5 6<br/>
6 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

