
# Description

<div class="content"><p><span style="font-size: medium">Byteland is a small country, with cities connected by N-1 bidirectional roads. From each city there is just one way of reaching every other city using the road network, which causes severe traffic jams. For this reason several highways have been built; each highway connects some pair of cities. <br/>
By a route we mean a sequence of roads and/or highways. All cities on a route should be distinct. For each pair of cities x,y there exists exactly one route which does not use any highway; we call such a route the main route between x and y . <br/>
People going from a city x to a city y can either choose the main route or use some highway. In the latter case the route cannot intersect the main route except for the cities x and  y and must contain exactly one highway. <br/>
Your task is to calculate the number of routes people can take between given pairs of cities. <br/>
</span></p>
<p><span style="font-size: medium">给一棵n个点的树以及m条额外的双向边<br/>
q次询问，统计满足以下条件的u到v的路径：<br/>
恰经过一条额外的边<br/>
不经过树上u到v的路径上的边<br/>
</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">The first line of input contains a single integer N（1&lt;=N&lt;=100000） - the number of cities in Byteland. Cities are numbered from 1 to n . Each of the next N -1 lines contains two integers Ai, Bi(1&lt;=Ai,Bi&lt;=N) meaning that cities Ai and Biare connected by a road. <br/>
The next line contains an integer M(1&lt;=M&lt;=100000) - the number of highways. Each of the next m lines contains a description of a single highway. The next line contains an integer Q (1&lt;=Q&lt;=500000) - the number of queries. Each of the next Q lines contains a description of a query. Both highways and queries are given in the same format as the roads. <br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">Your program should output exactly Q lines. The i-th line should contain the number of routes in the i-th query. <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
1 2<br/>
2 3<br/>
4 2<br/>
1 5<br/>
5 6<br/>
7 5<br/>
7 8<br/>
9 7<br/>
4<br/>
2 5<br/>
3 4<br/>
6 4<br/>
8 3<br/>
4<br/>
4 9<br/>
2 5<br/>
1 6<br/>
1 7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
4<br/>
2<br/>
2<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

