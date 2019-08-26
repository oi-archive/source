
# Description

<div class="content"><div style="text-indent: 24.1pt"><span style="font-size: 12pt">数学中有很多不等式，比如，当</span><span style="font-size: 12pt">x,y&gt;0</span><span style="font-size: 12pt">时：</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">x<sup>2</sup>+y<sup>2</sup>≥2xy</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">x<sup>3</sup>+y<sup>3</sup>≥x<sup>2</sup>y+xy<sup>2</sup></span></div>
<div style="text-indent: 24.1pt"><span style="font-size: 12pt">输入两个分别齐次且系数非负的二元多项式</span><span style="font-size: 12pt">f(x,y)</span><span style="font-size: 12pt">和</span><span style="font-size: 12pt">g(x,y)</span><span style="font-size: 12pt">，判断是否存在</span><span style="font-size: 12pt">A,r&gt;0</span><span style="font-size: 12pt">，满足对于任意</span><span style="font-size: 12pt">x,y&gt;0</span><span style="font-size: 12pt">，都有：</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">f(x,y)≥A*[g(x,y)]<sup>r</sup></span></div></div>

# Input

<div class="content"><div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">包含多组数据，相邻两组数据之间用一个空行隔开。</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">每组数据包含两行</span><span style="font-size: 12pt; line-height: 200%">.</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">第一行包括</span><span style="font-size: 12pt; line-height: 200%">n+2</span><span style="font-size: 12pt; line-height: 200%">个非负整数，</span><span style="font-size: 12pt; line-height: 200%">n,a<sub>0</sub>,a<sub>1</sub>,…,a<sub>n</sub></span><span style="font-size: 12pt; line-height: 200%">，</span><span style="font-size: 12pt; line-height: 200%">a<sub>i</sub></span><span style="font-size: 12pt; line-height: 200%">不全是</span><span style="font-size: 12pt; line-height: 200%">0.</span><span style="font-size: 12pt; line-height: 200%">表示</span><span style="font-size: 12pt; line-height: 200%">f(x,y)=a<sub>0</sub>x<sup>n</sup>+a<sub>1</sub>x<sup>n-1</sup>y+……+a<sub>n</sub>y<sup>n</sup>.</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">第二行包括</span><span style="font-size: 12pt; line-height: 200%">m+2</span><span style="font-size: 12pt; line-height: 200%">个非负整数</span><span style="font-size: 12pt; line-height: 200%">，</span><span style="font-size: 12pt; line-height: 200%">m,b<sub>0</sub>,b<sub>1</sub>,…,b<sub>m</sub></span><span style="font-size: 12pt; line-height: 200%">，</span><span style="font-size: 12pt; line-height: 200%">b<sub>i</sub></span><span style="font-size: 12pt; line-height: 200%">不全是</span><span style="font-size: 12pt; line-height: 200%">0.</span><span style="font-size: 12pt; line-height: 200%">表示</span><span style="font-size: 12pt; line-height: 200%">g(x,y)=b<sub>0</sub>x<sup>m</sup>+b<sub>1</sub>x<sup>m-1</sup>y+……+b<sub>m</sub>y<sup>m</sup>.</span></div></div>

# Output

<div class="content"><div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">对于每组数据，输出一行，若存在则输出</span><span style="font-size: 12pt; line-height: 200%">”YES”</span><span style="font-size: 12pt; line-height: 200%">，否则输出</span><span style="font-size: 12pt; line-height: 200%">”NO”.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 1 1<br/>
2 0 1 0<br/>
 <br/>
2 1 1 1<br/>
3 1 0 0 1<br/>
 <br/>
5 1 0 0 1 0 0<br/>
5 0 0 1 0 0 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
YES<br/>
NO<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例说明】<br/><br/>
数据1：x+y≥2[(xy)1/2]；<br/><br/>
数据2：x2+xy+y2≥(x3+y3)2/3，展开易证；<br/><br/>
数据3：反设x5+x2y3≥A*(x3y2+y5)r，对于所有正数x,y成立.取x=y，得：2x5≥A(2x5)r，若r&gt;1,则x取足够大时不等式不成立，若r&lt;1,则x取足够小时不等式不成立，所以r=1；<br/><br/>
再取x=1，得：1+y3≥A*(y2+y5)，即：1≥Ay2，不可能对所有正数y成立，故不存在A,r.<br/><br/>
【数据规模】<br/><br/>
最多包含100组数据，且1&lt;=n,m&lt;=100，系数大小不超过10000.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

