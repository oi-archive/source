
# Description

<div class="content"><div>在Byteland 一共有n 座城市，编号依次为1 到n，这些城市之间通过m 条单向公路连接。对于两座不同的城市a 和</div>
<div>b，如果a 能通过这些单向道路直接或间接到达b，且b 也能如此到达a，那么它们就会被认为是一对友好城市。Byt</div>
<div>eland 的交通系统十分特殊，第i 天只有编号在[li, ri] 的单向公路允许通行，请写一个程序，计算每天友好城</div>
<div>市的对数。</div>
<div>注意：(a, b) 与(b, a) 没有区别。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含三个正整数n, m, q，分别表示城市的个数、单向公路的条数以及询问的天数。</div>
<div>接下来m 行，每行两个正整数ui, vi，表示一条从城市ui 出发，通往城市vi 的单向道路。</div>
<div>接下来q 行，每行两个正整数li, ri，表示一个询问。</div>
<div>1 ≤ ui, vi ≤ n, ui != vi, 1 ≤ li ≤ ri ≤ m。N&lt;=150,M&lt;=300000,Q&lt;=50000</div>
<div></div></div>

# Output

<div class="content"><div>输出q 行，每行一个整数，即友好城市的对数。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 3<br/>
1 2<br/>
2 3<br/>
2 1<br/>
1 1<br/>
1 2<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Claris原创，本站版权所有">Claris原创，本站版权所有</a></p></div>

