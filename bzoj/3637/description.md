
# Description

<div class="content"><div class="legend">
<p><span style="font-size: medium">You are given a tree (an acyclic undirected connected graph) with <span class="tex-span"><i>n</i></span> nodes. The tree nodes are numbered from 1 to <span class="tex-span"><i>n</i></span>. </span></p>
<p><span style="font-size: medium">Each node has a color, white or black. All the nodes are black initially.</span></p>
<p><span style="font-size: medium">We will ask you to perfrom some instructions of the following form:</span></p>
<p></p>
<ul type="disc">
    <li><span style="font-size: medium">0 <span class="tex-span"><i>u</i></span> : ask for how many nodes are connected to <span class="tex-span"><i>u</i></span>, two nodes are connected iff all the node on the path from <span class="tex-span"><i>u</i></span> to <span class="tex-span"><i>v</i></span> (inclusive <span class="tex-span"><i>u</i></span> and <span class="tex-span"><i>v</i></span>) have a same color. </span></li>
    <li><span style="font-size: medium">1 <span class="tex-span"><i>u</i></span> : toggle the color of <span class="tex-span"><i>u</i></span>(that is, from black to white, or from white to black). </span></li>
</ul>
</div>
<p></p>
<p></p>
<div class="input-specification">
<p></p>
</div></div>

# Input

<div class="content"><div class="input-specification">
<p></p>
<p><span style="font-size: medium">The first line contains a number <span class="tex-span"><i>n</i></span> denoted how many nodes in the tree(<span class="tex-span">1 ≤ <i>n</i> ≤ 10<sup class="upper-index">5</sup></span>). The next <span class="tex-span"><i>n</i> - 1</span> lines, each line has two numbers (<span class="tex-span"><i>u</i>,  <i>v</i></span>) describe a edge of the tree(<span class="tex-span">1 ≤ <i>u</i>,  <i>v</i> ≤ <i>n</i></span>). The next line contains a number <span class="tex-span"><i>m</i></span> denoted how many operations we are going to process(<span class="tex-span">1 ≤ <i>m</i> ≤ 10<sup class="upper-index">5</sup></span>). The next <span class="tex-span"><i>m</i></span> lines, each line describe a operation (<span class="tex-span"><i>t</i>,  <i>u</i></span>) as we mentioned above(<span class="tex-span">0 ≤ <i>t</i> ≤ 1</span>, <span class="tex-span">1 ≤ <i>u</i> ≤ <i>n</i></span>).</span></p>
</div>
<p></p>
<p></p>
<div class="output-specification"></div></div>

# Output

<div class="content"><div class="output-specification">
<div class="section-title"> </div>
<p></p>
<p><span style="font-size: medium">For each query operation, output the corresponding result.</span></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
1 3<br/>
1 4<br/>
1 5<br/>
3<br/>
0 1<br/>
1 1<br/>
0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By xiaodao">By xiaodao</a></p></div>

