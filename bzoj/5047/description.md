
# Description

<div class="content"><div>太空中一共有n座星球，它们之间可以通过空间传送装置进行转移。空间传送装置分为m种，第i种装置可以用4个参</div>
<div>数a_i,b_i,c_i,d_i来描述。因为时空抖动的问题，在非整数时刻禁止使用空间传送装置。如果在整数s时刻使用装</div>
<div>置，那么需要花费((a_i*s+b_i) mod c_i)+d_i单位时间才能完成传送。现在是s时刻，小Q位于1号星球，请写一个</div>
<div>程序计算从1号星球到每个星球最少需要的时间。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含4个正整数n,m,s,e(2&lt;=n&lt;=100000,1&lt;=m&lt;=50,1&lt;=s&lt;=2000,1&lt;=e&lt;=200000)</div>
<div>分别表示星球的个数、空间传送装置的种类数、当前的时间以及空间传送装置的个数。</div>
<div>接下来m行，每行4个正整数a_i,b_i,c_i,d_i(1&lt;=a_i,b_i,c_i,d_i&lt;=2000)，依次描述每种装置的参数。</div>
<div>接下来e行，每行3个正整数u_i,v_i,w_i(1&lt;=u_i,v_i&lt;=n,u_i!=v_i,1&lt;=w_i&lt;=m)</div>
<div>表示从星球u_i可以使用第w_i种装置单向传送到星球v_i。</div>
<div></div></div>

# Output

<div class="content"><div>输出n-1行，每行一个整数，第i行表示从1到i+1的最少所需时间，若无解输出-1。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 1 3<br/>
1 1 5 1<br/>
2 2 7 1<br/>
1 2 1<br/>
2 3 2<br/>
3 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
6<br/>
<br/>
HINT<br/>
1到3：在时刻1使用第一种装置从1传送到2，花费时间3，再等待2单位时间，于时刻6使用第二种装置到达3，花费时间1。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

