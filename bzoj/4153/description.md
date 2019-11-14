
# Description

<div class="content"><div>
<div>有n对夫妇,一开始夫妇之间互不认识,若两男或两女成为朋友,称他们为&#34;熟人&#34;,&#34;熟人&#34;关系具有传递性,即若a熟b且b熟c则a熟c.若两组夫妇的丈夫互相为熟人且妻子也相互为熟人则称他们为&#34;熟悉的一对&#34;,现在给出q个事件,每个事件会使得两男或两女成为朋友,并在每次事件之后计算&#34;熟悉的一对&#34;的个数.</div>
</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行一个数T表示数据组数</div>
<div>接下来n,q表示对数和事件数</div>
<div>接下来q行,每行t,a,b,若t=1,表示男a和男b成为朋友,t=2,表示女a和女b成为朋友</div>
</div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>设当前是第i个操作,y_i为本次事件之后的答案,令z_i=i*y_i,请输出z_1+z_2+...+z_q模10^9+7</div>
</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3 5<br/>
1 1 2<br/>
2 1 3<br/>
1 2 3<br/>
1 3 1<br/>
2 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">22<br/>
<br/>
样例解释<br/>
1*0+2*0+3*1+4*1+5*3=22<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div>T&lt;=8</div><br/>
<div><span style="color: rgb(255, 0, 0);">n,q&lt;=10^6</span></div><br/>
<div></div><br/>
</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

