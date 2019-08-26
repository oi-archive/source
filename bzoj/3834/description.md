
# Description

<div class="content"><div>Having decided to invest in renewable energy, Byteasar started a solar panels factory. It appears that he has hit the gold as within a few days  clients walked through his door. Each client has ordered a single rectangular panel with specified width and height ranges.</div>
<div>The panels consist of square photovoltaic cells. The cells are available in all integer sizes, i.e., with the side length integer, but all cells in one panel have to be of the same size. The production process exhibits economies of scale in that the larger the cells that form it, the more efficient the panel. Thus, for each of the ordered panels, Byteasar would like to know the maximum side length of the cells it can be made of.</div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">n组询问，每次问smin&lt;=x&lt;=smax, wmin&lt;=y&lt;=wmax时gcd(x, y)的最大值。</span></div>
<p></p></div>

# Input

<div class="content"><div>The first line of the standard input contains a single integer N(1&lt;=N&lt;=1000): the number of panels that were ordered. The following   lines describe each of those panels: the i-th line contains four integers Smin,Smax,Wmin,Wmax(1&lt;=Smin&lt;=Smax&lt;=10^9,1&lt;=Wmin&lt;=Wmax&lt;=10^9), separated by single spaces; these specify the minimum width, the maximum width, the minimum height, and the maximum height of the i-th panel respectively.</div>
<p></p></div>

# Output

<div class="content"><div>Your program should print exactly n lines to the standard output. The i-th line is to give the maximum side length of the cells that the i-th panel can be made of.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3 9 8 8<br/>
1 10 11 15<br/>
4 7 22 23<br/>
2 5 19 24</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
7<br/>
2<br/>
5</span></div>

# Hint

<div class="content"><p></p><div>Explanation: Byteasar will produce four solar panels of the following sizes: 8*8 (a single cell), 7*14 (two cells), 4*22 or 6*22 (22 or 33 cells respectively), and 5*20 (four cells).</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢zhonghaoxi">鸣谢zhonghaoxi</a></p></div>

