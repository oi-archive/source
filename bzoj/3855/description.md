
# Description

<div class="content"><div>Teacher Mai has a board of n rows and m columns. There is a light in each cell.</div>
<div></div>
<div>He can flip some lights: if this light is on, turn it off, else turn it on.</div>
<div></div>
<div>He can choose a cell(i,j), and he has following two operations:</div>
<div></div>
<div>1. Flip the light on the cells which share a common edge with cell(i,j).</div>
<div>2. Flip the light on the cells which share a common edge with cell(i,j) and cell(i,j).</div>
<div>  </div>
<div>You are given the initial state of board. Output the minimum operations to turn off the all the lights.</div>
<p></p></div>

# Input

<div class="content"><div>There are multiple test cases, terminated by a line &#34;0 0&#34;.</div>
<div>
<div></div>
<div>For each test case, the first line contains two integers n,m(1&lt;=n,m&lt;=10).</div>
<div></div>
<div>In following n lines, each line contains a string consisting of m characters, representing the initial state(0 means off, 1 means on).</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>For each case, output &#34;Case #k: ans&#34; first, where k is the case number counting from 1, ans is the minimum operations.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
111<br/>
111<br/>
111<br/>
3 3<br/>
000<br/>
010<br/>
000<br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 3<br/>
Case #2: 2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

