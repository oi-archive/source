
# Description

<div class="content"><p><span style="font-size: medium">Tao Yuanming(365-427) was a Chinese poet of Eastern Jin dynasty. One of his most famous works is &#34;Peach Blossom Spring&#34;, which is a fable about a chance<br/>
discovery of an ethereal village where the people lead an ideal existence in harmony with nature, unaware of the outside world for centuries. So in Chinese, &#34;Peach Blossom Spring&#34; means &#34;utopia&#34;.<br/>
In the story of &#34;Peach Blossom Spring&#34;, there was a mysterious place. In Qin dynasty, some people escaped to that place during the civil unrest and built a village. They and their descendants never left and never had any contact with the outside world since then, until centuries latter a fisherman of Jin dynasty found them.<br/>
Recently, some Chinese ACMers happened to find the relics of the village mentioned in&#34;Peach Blossom Spring&#34;.<br/>
They also found a document about building hiding places to escape from Qin army. The document said:<br/>
There were n houses and m roads in the village. Each road connected two houses. These houses were numbered from 1 to n. There were k families, each living in a different house. <br/>
The houses they lived were house 1, house 2, … , house k. There were also k broken houses: house n-k+1, house n-k+2, ... , house n, with secret basements so that those houses could be used as hiding places.<br/>
The problem was that all roads were broken. People wanted to repair some roads so that every family could reach a hiding place through the repaired roads. Every hiding place could only hold one family. Each road cost some labor to be repaired. The head of the village wanted to find out the minimum cost way of repairing the roads, but he didn&#39;t know how to do.<br/>
Would you solve the problem which the ancient village head never solved?</span></p></div>

# Input

<div class="content"><div class="panel_content"><span style="font-size: medium">the first line begins with three integers ---- the above mentioned <span style="color: #ff0000">n (n&lt;=7000), m (0&lt;=m&lt;=10000) </span>and k (1&lt;=k&lt;=5, 2k&lt;=n). Then m lines follow, each containing three integers u,v and w, indicating that there is a broken road connecting house u an d v, and the cost to repair that road is w(1&lt;=w&lt;=1000).</span></div></div>

# Output

<div class="content"><div class="panel_content"><span style="font-size: medium"> if you cannot find a proper way to repair the roads, output  <span style="color: #ff0000">-1</span>  in a line. Otherwise, output the minimum cost to repair the roads in a line.</span></div>
<div class="panel_bottom"></div>
<div class="panel_content">
<pre>	</pre>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">input 1<br/>
4 3 1<br/>
4 2 10<br/>
3 1 9<br/>
2 3 10<br/>
<br/>
input 2<br/>
6 7 2<br/>
1 5 1000<br/>
2 6 1000<br/>
1 3 1<br/>
2 3 1<br/>
3 4 1<br/>
4 5 1<br/>
4 6 1<br/>
 <br/>
<br/>
 <br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">output 1<br/>
29<br/>
<br/>
<br/>
output 2<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=斯坦纳树">斯坦纳树</a></p></div>

