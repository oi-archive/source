
# Description

<div class="content"><div>
<div>农场面临着洪水的威胁。帮助约翰找到水的高度，他可以把他的奶牛移到安全的地方, 农场由M×N(1≤M，N≤400)</div>
<div>的单位方格组成．每格有一个海拔高度Hi，j(1≤Hi，j≤10000)．给出一个M×N的表格地图和降水量V(1≤V≤10^9</div>
<div>)。水总是先注入最低的方格，不管该方格在哪儿。请你算出水面高度，水面和海平面之间的陆地体积（可能为0）</div>
<div>。注意：陆地和水面高度相同时已经被淹没。</div>
<div></div>
<div></div>
</div></div>

# Input

<div class="content"><div><span style="font-size: medium;">* Line 1: Three space-separated integers: M, N,  and V</span></div>
<div><font size="3">* Lines 2...: Each line contains as many as 20 space-separated</font></div>
<div><font size="3">        integers that represent the elevations of the farm. The first</font></div>
<div><font size="3">        N integers are spread across line 1 and it successors, 20</font></div>
<div><font size="3">        integers per line, until all N integers are laid out. The next</font></div>
<div><font size="3">        N integers begin on a new line, etc.</font></div>
<div></div></div>

# Output

<div class="content"><div>在一行内输出两个由空格分隔的整数：水面高度，海平面和水面之间陆地的体积（被水完全淹没的陆地体积）。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 33<br/>
2 2 2 2 2<br/>
1 3 4 3 2<br/>
2 3 5 3 2<br/>
2 4 1 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">4  43<br/>
</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div>The water will rise to a height of 4 m, submerging the blocks marked1, 2, 3, and 4.</div><br/>
<div>The volume of land below the water is 1*3 + 2*10 + 3*4 +4*2 = 43.</div><br/>
<div>水高4米，淹没的区域标记1，2，3，4．水下陆地的体积：1×3+2×10+3×4+4×2=43.</div><br/>
</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Orange">Orange</a></p></div>

