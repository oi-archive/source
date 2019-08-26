
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">Tired of the cold winter weather on her farm, Bessie the cow plans to fly to a warmer destination for vacation.  Unfortunately, she discovers that only one airline, Air Bovinia, is willing to sell tickets to cows, and that these tickets are somewhat complicated in structure.  Air Bovinia owns N planes (1 &lt;= N &lt;= 1000), each of which flies on a specific &#34;route&#34; consisting of two or more cities.  For example, one plane might fly on a route that starts at city 1, then flies to city 5, then flies to city 2, and then finally flies to city 8.  No city appears multiple times in a route.  If Bessie chooses to utilize a route, she can board at any city along the route and then disembark at any city later along the route.  She does not need to board at the first city or disembark at the last city.  Each route has a certain cost, which Bessie must pay if she uses any part of the route, irrespective of the number of cities she visits along the route.  If Bessie uses a route multiple times during her travel (that is, if she leaves the route and later comes back to use it from antoher city), she must pay for it each time it is used.  Bessie would like to find the cheapest way to travel from her farm (in city A) to her tropical destination (city B). Please help her decide what is the minimum cost she must pay, and also the smallest number of individual flights she must use take to achieve this minimum cost.<br/>
</span></p>
<div>第一行 s，t，m表示：起点，终点，m条航线。</div>
<div>然后m组，每组第一行len，n表示这条航线的代价， </div>
<div>这类似于公交车，只要用了就花这些钱，但是用多少都这些钱。 </div>
<div>注意是单向边。</div>
<div>举例： </div>
<div>2333 4 </div>
<div>3 2 1 4 </div>
<div>就是3-&gt;2、3-&gt;1、3-&gt;4、2-&gt;1、2-&gt;4、1-&gt;4都花2333元。</div>
<div>这个花销是第一键值。 </div>
<div>第二键值是经过几站。</div>
<div>比如3-&gt;2-&gt;1-&gt;4花费2333 </div>
<div>而如果有其它航线使得3-&gt;5-&gt;4花费1000+1333==2333的话， </div>
<div>那么因为它经过了2站，所以更优。</div>
<div>然后求双键值最短路。 </div>
<div>输出这俩键值。</div>
<div>无解输出“-1 -1”。</div>
<p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;"> </span></p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line of input contains A, B, and N, separated by spaces.   The next 2N lines describe the available routes, in two lines per route. The first line contains the cost of using the route (an integer in the range 1..1,000,000,000), and the number of cities along the route (an integer in the range 1..100).  The second line contains a list of the cities in order along the route.  Each city is identified by an integer in the range 1..1000.  Note that the cost of an itinerary can easily add up to more than can fit into a 32-bit integer, so you should probably use 64-bit integers (e.g., &#34;long long&#34; integers in C/C++).<br/>
</span></div>
<p></p></div>

# Output

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">Output the minimum cost of an itinerary that Bessie can use to travel from city A to city B, as well as the minimum number of individual flights required to achieve this minimum cost.  If there is no solution, output &#34;-1 -1&#34; (quotes for clarity) on a single line.<br/>
</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 3<br/>
3 5<br/>
1 2 3 4 5<br/>
2 3<br/>
3 5 4<br/>
1 2<br/>
1 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

