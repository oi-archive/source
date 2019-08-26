
# Description

<div class="content"><div>Autumn终于会求区间逆序对了!Bakser神犇决定再考验一下他，他说道：</div>
<div></div>
<div>“在Gty的妹子序列里，某个妹子的美丽度可也是会变化的呢。你还能求出某个区间</div>
<div></div>
<div>中妹子们美丽度的逆序对数吗？当然，为了方便，这次我们规定妹子们的美丽度在</div>
<div></div>
<div>[1,n]中。仍然强制在线。”</div>
<div></div>
<div>Autumn需要你的帮助。</div>
<div></div>
<div>给定一个正整数序列a(1&lt;=ai&lt;=n)，支持单点修改，对于每次询问，输出al...ar中</div>
<div></div>
<div>的逆序对数，强制在线。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括一个整数n(1&lt;=n&lt;=50000),表示数列a中的元素数。</div>
<div></div>
<div>第二行包括n个整数a1...an(1&lt;=ai&lt;=n)。</div>
<div></div>
<div>接下来一行包括一个整数m(1&lt;=m&lt;=50000),表示操作的个数。</div>
<div></div>
<div>接下来m行,每行包括3个整数。</div>
<div></div>
<div>0 L R (1&lt;=L&lt;=R&lt;=n) 询问[L,R]中的逆序对数。</div>
<div></div>
<div>1 p v (1&lt;=p&lt;=n,1&lt;=v&lt;=n) 将p位置的数修改为v。</div>
<div></div>
<div>L,R,p,v 都需要异或上一次的答案，保证异或之后的值是合法的。</div>
<div></div>
<div>保证涉及的所有数在int内。</div>
<p></p></div>

# Output

<div class="content"><p>对每个询问，单独输出一行，表示al...ar中的逆序对数。对每个询问，单独输出一行，表示al...ar中的逆序对数。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1 7 5 6 9 4 9 4 4 7<br/>
10<br/>
0 4 6<br/>
0 5 8<br/>
0 1 10<br/>
1 25 19<br/>
0 19 25<br/>
1 14 4<br/>
0 12 12<br/>
0 2 5<br/>
1 8 7<br/>
1 1 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
16<br/>
13<br/>
0<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Autumn">By Autumn</a></p></div>

