
# Description

<div class="content"><div>农夫Byteasar买了一片n亩的土地，他要在这上面种草。</div>
<div>他在每一亩土地上都种植了一种独一无二的草，其中，第i亩土地的草每天会长高a[i]厘米。</div>
<div>Byteasar一共会进行m次收割，其中第i次收割在第d[i]天，并把所有高度大于等于b[i]的部分全部割去。Byteasar想知道，每次收割得到的草的高度总和是多少，你能帮帮他吗？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n,m&lt;=500000)，分别表示亩数和收割次数。</div>
<div>第二行包含n个正整数，其中第i个数为a[i](1&lt;=a[i]&lt;=1000000)，依次表示每亩种植的草的生长能力。</div>
<div>接下来m行，每行包含两个正整数d[i],b[i](1&lt;=d[i]&lt;=10^12，0&lt;=b[i]&lt;=10^12)，依次描述每次收割。</div>
<div>数据保证d[1]&lt;d[2]&lt;...&lt;d[m]，并且任何时刻没有任何一亩草的高度超过10^12。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出m行，每行一个整数，依次回答每次收割能得到的草的高度总和。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 4 3<br/>
1 1<br/>
2 2<br/>
3 0<br/>
4 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
6<br/>
18<br/>
0</span></div>

# Hint

<div class="content"><p></p><div>第1天，草的高度分别为1,2,4,3，收割后变为1,1,1,1。</div><br/>
<div>第2天，草的高度分别为2,3,5,4，收割后变为2,2,2,2。</div><br/>
<div>第3天，草的高度分别为3,4,6,5，收割后变为0,0,0,0。</div><br/>
<div>第4天，草的高度分别为1,2,4,3，收割后变为1,2,4,3。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

