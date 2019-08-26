
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">给定函数</span><span style="font-size: 12pt">f(x) </span><span style="font-size: 12pt">，它在</span><span style="font-size: 12pt">[k,k+1]</span><span style="font-size: 12pt">上是线性的，</span><span style="font-size: 12pt">x</span><span style="font-size: 12pt">是整数时，</span><span style="font-size: 12pt">f(x)</span><span style="font-size: 12pt">也是整数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">即当</span><span style="font-size: 12pt">k</span><span style="font-size: 12pt">是整数时，</span><span style="font-size: 12pt">x</span><span style="font-size: 12pt">属于</span><span style="font-size: 12pt">[k,k+1]</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">f(x)=(k+1-x)f(k)+(x-k)f(k+1)</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">记</span><span style="font-size: 12pt">f^1(x)=f(x),f^n(x)=f(f^(n-1)(x))</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">给出</span><span style="font-size: 12pt">f(0),f(1),...,f(m)</span><span style="font-size: 12pt">，求</span><span style="font-size: 12pt">f^n(x)=x </span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">x</span><span style="font-size: 12pt">属于</span><span style="font-size: 12pt">[0,m]</span><span style="font-size: 12pt">的解的个数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">多组数据。</span></div>
<div style="text-indent: 21pt"><sup> </sup></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 10.5pt">对于每组数据：</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">第一行读入一个数</span><span style="font-size: 10.5pt">m</span><span style="font-size: 10.5pt">。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">第二行读入</span><span style="font-size: 10.5pt">m+1</span><span style="font-size: 10.5pt">个数，第</span><span style="font-size: 10.5pt">i</span><span style="font-size: 10.5pt">个数表示</span><span style="font-size: 10.5pt">f(i-1)</span><span style="font-size: 10.5pt">。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">第三行读入两个数</span><span style="font-size: 10.5pt">n</span><span style="font-size: 10.5pt">和</span><span style="font-size: 10.5pt">modnum</span><span style="font-size: 10.5pt">，</span><span style="font-size: 10.5pt">modnum</span><span style="font-size: 10.5pt">表示答案需要</span><span style="font-size: 10.5pt">mod modnum</span><span style="font-size: 10.5pt">。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">相邻两组数据中有一个空行。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">最后以</span><span style="font-size: 10.5pt">0</span><span style="font-size: 10.5pt">结束。</span></div>
<div style="text-indent: 21pt"> </div>
<div style="text-indent: 21pt"></div>
<div> </div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 10.5pt">对于每组数据输出一行表示答案。如果有无穷多个输出</span><span style="font-size: 10.5pt">Infinity</span><span style="font-size: 10.5pt">。</span></div>
<div style="text-indent: 21pt"> </div>
<div></div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 0 2<br/>
2 10<br/>
 <br/>
3<br/>
0 1 3 2<br/>
1 137<br/>
 <br/>
3<br/>
2 3 0 3<br/>
20 10000<br/>
 <br/>
0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
Infinity<br/>
9074<br/>
 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p>对于100%，n&lt;=5000,m&lt;=80,modnum&lt;=10000。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

