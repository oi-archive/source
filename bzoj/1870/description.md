
# Description

<div class="content"><div>给出N条直线，问他们将一个无限大平面分成了多少份，每一份的面积是多少。</div>
<div>（N&lt;=80，不考虑面积小于1e-8的多边形）</div></div>

# Input

<div class="content"><div>The first line of the input file contains N  </div>
<div>the number of lines (1 &lt;= N &lt;= 80). </div>
<div>Each of next N lines contains four integer numbers x1, y1, x2 and y2 </div>
<div>- the coordinates of two different points of the line. </div>
<div>All coordinates do not exceed 102 by their absolute value. No two lines coincide.</div></div>

# Output

<div class="content"><div>First output K - the number of finite parts among those the lines divide the plane to. </div>
<div>Next K lines of the output file must contain area parts sorted in non-decreasing order. </div>
<div>You answer must be accurate up to 10-4. Due to floating point precision losses possible, </div>
<div>do not consider parts with area not exceeding 10-8.</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5<br/>
0 0 1 0<br/>
1 0 1 1<br/>
1 1 0 1<br/>
0 1 0 0<br/>
0 0 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0.5000<br/>
0.5000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

