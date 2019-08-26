
# Description

<div class="content"><div class="header">
<div class="time-limit"><span style="font-size: medium">You are given a tree (an acyclic undirected connected graph) with <span class="tex-span"><i>n</i></span> nodes. The tree nodes are numbered from 1 to <span class="tex-span"><i>n</i></span>. </span></div>
</div>
<div class="legend">
<p><span style="font-size: medium">Each node has a color, white or black, and a weight.</span></p>
<p><span style="font-size: medium">We will ask you to perfrom some instructions of the following form:</span></p>
<p></p>
<ul type="disc">
    <li><span style="font-size: medium">0 <span class="tex-span"><i>u</i></span> : ask for the maximum weight among the nodes which are connected to <span class="tex-span"><i>u</i></span>, two nodes are connected iff all the node on the path from <span class="tex-span"><i>u</i></span> to <span class="tex-span"><i>v</i></span> (inclusive <span class="tex-span"><i>u</i></span> and <span class="tex-span"><i>v</i></span>) have a same color. </span></li>
    <li><span style="font-size: medium">1 <span class="tex-span"><i>u</i></span> : toggle the color of <span class="tex-span"><i>u</i></span>(that is, from black to white, or from white to black). </span></li>
    <li><span style="font-size: medium">2 <span class="tex-span"><i>u</i></span> <span class="tex-span"><i>w</i></span>: change the weight of <span class="tex-span"><i>u</i></span> to <span class="tex-span"><i>w</i></span>. </span></li>
</ul>
</div>
<p></p>
<p></p>
<div class="input-specification"></div></div>

# Input

<div class="content"><div class="input-specification">
<p><span style="font-size: medium">The first line contains a number <span class="tex-span"><i>n</i></span> denoted how many nodes in the tree(<span class="tex-span">1 ≤ <i>n</i> ≤ 10<sup class="upper-index">5</sup></span>). The next <span class="tex-span"><i>n</i> - 1</span> lines, each line has two numbers (<span class="tex-span"><i>u</i>,  <i>v</i></span>) describe a edge of the tree(<span class="tex-span">1 ≤ <i>u</i>,  <i>v</i> ≤ <i>n</i></span>). </span></p>
<p><span style="font-size: medium">The next 2 lines, each line contains <span class="tex-span"><i>n</i></span> number, the first line is the initial color of each node(0 or 1), and the second line is the initial weight, let&#39;s say <span class="tex-span"><i>W</i><sub class="lower-index"><i>i</i></sub></span>, of each node(<span class="tex-span">|<i>W</i><sub class="lower-index"><i>i</i></sub>| ≤ 10<sup class="upper-index">9</sup></span>).</span></p>
<p><span style="font-size: medium">The next line contains a number <span class="tex-span"><i>m</i></span> denoted how many operations we are going to process(<span class="tex-span">1 ≤ <i>m</i> ≤ 10<sup class="upper-index">5</sup></span>). The next <span class="tex-span"><i>m</i></span> lines, each line describe a operation (<span class="tex-span"><i>t</i>,  <i>u</i></span>) as we mentioned above(<span class="tex-span">0 ≤ <i>t</i> ≤ 2</span>, <span class="tex-span">1 ≤ <i>u</i> ≤ <i>n</i></span>, <span class="tex-span">|<i>w</i>| ≤ 10<sup class="upper-index">9</sup></span>).</span></p>
</div>
<p></p>
<p></p>
<div class="output-specification"></div></div>

# Output

<div class="content"><div class="output-specification">
<p><span style="font-size: medium">For each query operation, output the corresponding result.</span></p>
</div>
<p></p>
<p></p>
<div class="sample-tests"></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
1 3<br/>
1 4<br/>
1 5<br/>
0 1 1 1 1<br/>
1 2 3 4 5<br/>
3<br/>
0 1<br/>
1 1<br/>
0 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By xiaodao">By xiaodao</a></p></div>

