
# Description

<div class="content"><div>经过一天辛苦的工作，小Q进入了梦乡。他脑海中浮现出了刚进大学时学01背包的情景，那时还是大一萌新的小Q解</div>
<div>决了一道简单的01背包问题。这个问题是这样的：给定n个物品，每个物品的体积分别为v_1,v_2,...,v_n，请计算</div>
<div>从中选择一些物品（也可以不选），使得总体积恰好为w的方案数。因为答案可能非常大，你只需要输出答案对P取</div>
<div>模的结果。因为长期熬夜刷题，他只看到样例输入中的w和P，以及样例输出是k，看不清到底有几个物品，也看不</div>
<div>清每个物品的体积是多少。直到梦醒，小Q也没有看清n和v，请写一个程序，帮助小Q一起回忆曾经的样例输入。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数T(1&lt;=T&lt;=100)，表示测试数据的组数。</div>
<div>接下来T行，每行3个整数w,P,k(50&lt;=w&lt;=20000,1&lt;=P&lt;=2^30,0&lt;=k&lt;=min(20000,P-1))</div>
<div>分别表示每组需要回忆的测试数据的相关参数。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，第一行输出n(1&lt;=n&lt;=40)。</div>
<div>第二行输出n个正整数v_1,v_2,...,v_n(1&lt;=v_i&lt;=20000)，分别表示每个物品的体积。</div>
<div>若有多组可行解，输出任意一组。输入数据保证对于每组数据至少存在一组可行解。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
50 1013 4<br/>
50 3 1<br/>
80 5 1<br/>
100 1000000007 13</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
10 20 20 30 50<br/>
5<br/>
10 20 20 30 50<br/>
8<br/>
10 20 30 40 50 60 70 80<br/>
11<br/>
12 18 20 13 41 30 15 11 11 250 28<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

