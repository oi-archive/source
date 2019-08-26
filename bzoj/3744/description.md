
# Description

<div class="content"><div>我早已习惯你不在身边，</div>
<div></div>
<div>人间四月天 寂寞断了弦。</div>
<div></div>
<div>回望身后蓝天，</div>
<div></div>
<div>跟再见说再见……</div>
<div></div>
<div></div>
<div>某天,蒟蒻Autumn发现了从 Gty的妹子树(bzoj3720) 上掉落下来了许多妹子,他发现</div>
<div></div>
<div>她们排成了一个序列,每个妹子有一个美丽度。</div>
<div></div>
<div>Bakser神犇与他打算研究一下这个妹子序列,于是Bakser神犇问道:&#34;你知道区间</div>
<div></div>
<div>[l,r]中妹子们美丽度的逆序对数吗?&#34;</div>
<div></div>
<div>蒟蒻Autumn只会离线乱搞啊……但是Bakser神犇说道:&#34;强制在线。&#34;</div>
<div></div>
<div>请你帮助一下Autumn吧。</div>
<div></div>
<div></div>
<div>给定一个正整数序列a,对于每次询问,输出al...ar中的逆序对数,强制在线。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括一个整数n(1&lt;=n&lt;=50000),表示数列a中的元素数。</div>
<div></div>
<div>第二行包括n个整数a1...an(ai&gt;0,保证ai在int内)。</div>
<div></div>
<div>接下来一行包括一个整数m(1&lt;=m&lt;=50000),表示询问的个数。</div>
<div></div>
<div>接下来m行,每行包括2个整数l、r(1&lt;=l&lt;=r&lt;=n),表示询问al...ar中的逆序</div>
<div></div>
<div>对数(若ai&gt;aj且i&lt;j,则为一个逆序对)。</div>
<div></div>
<div>l,r要分别异或上一次询问的答案(lastans),最开始时lastans=0。</div>
<div></div>
<div>保证涉及的所有数在int内。</div>
<p></p></div>

# Output

<div class="content"><p>对每个询问,单独输出一行,表示al...ar中的逆序对数。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 4 2 3<br/>
1<br/>
2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Autumn">By Autumn</a></p></div>

