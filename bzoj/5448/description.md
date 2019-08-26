
# Description

<div class="content"><div>有n个变量w[1]~w[n]，每个变量可以取W或-W。</div>
<div>有p个式子，形如Hi=ai|w[xi]-w[yi]|+bi|w[yi]-w[zi]|+ci|w[zi]-w[xi]|</div>
<div>+di(w[xi]-w[yi])+ei(w[yi]-w[zi])+fi(w[zi]-w[xi])。</div>
<div>有q个条件，形如w[x]&lt;=w[y]或w[x]=w[y]或w[x]&lt;w[y]。</div>
<div>最小化sigma(wi)+sigma(Hi)。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数t表示数据组数。</div>
<div>每组数据第一行四个整数n,W,p,q表示节点数。</div>
<div>接下来p行每行九个整数xi,yi,zi,ai,bi,ci,di,ei,fi。</div>
<div>接下来q行每行三个整数x,y,r。</div>
<div>r=0表示w[x]&lt;=w[y]；r=1表示w[x]=w[y]；r=2表示w[x]&lt;w[y]。</div>
<div>保证存在方案。</div>
<div>t&lt;=10，n&lt;=500，p,q&lt;=1000，1&lt;=W&lt;=10^6，</div>
<div>0&lt;=ai,bi,ci,di,ei,fi&lt;=1000。</div>
<p></p></div>

# Output

<div class="content"><div>每组数据输出一行一个整数表示sigma(wi)+sigma(Hi)的最小值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3 1 1 1<br/>
1 2 3 1 1 1 1 1 1 <br/>
1 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

