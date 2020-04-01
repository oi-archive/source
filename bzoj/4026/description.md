
# Description

<div class="content"><div>
<div> dC 在秒了BZOJ 上所有的数论题后，感觉萌萌哒，想出了这么一道水题，来拯救日益枯</div>
<div>竭的水题资源。 </div>
<div>  给定一个长度为 n的正整数序列A，有q次询问，每次询问一段区间内所有元素乘积的</div>
<div>φ（φ(n)代表1~n 中与n互质的数的个数） 。由于答案可能很大，所以请对答案 mod 10^6 + </div>
<div>777。 （本题强制在线，所有询问操作的l,r都需要 xor上一次询问的答案 lastans，初始时，</div>
<div>lastans = 0） </div>
</div>
<p></p></div>

# Input

<div class="content"><p> 第一行，两个正整数，N，Q，表示序列的长度和询问的个数。 </p>
<div>第二行有N 个正整数，第i个表示Ai. </div>
<div>下面Q行，每行两个正整数，l r，表示询问[l ^ lastans,r ^ lastans]内所有元素乘积的φ </div></div>

# Output

<div class="content"><p>Q行，对于每个询问输出一个整数。 </p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
3 7 10 10 5 <br/>
3 4<br/>
42 44<br/>
241 242<br/>
14 9<br/>
1201 1201<br/>
0 6<br/>
245 245<br/>
7 7<br/>
6 1<br/>
1203 1203<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">40<br/>
240<br/>
12<br/>
1200<br/>
2<br/>
240<br/>
4<br/>
4<br/>
1200<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 1 &lt;= N &lt;= 50000 </p><br/>
<div>1 &lt;= Q &lt;= 100000 </div><br/>
<div>1 &lt;= Ai &lt;= 10^6 </div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=orz Loidc">orz Loidc</a></p></div>

