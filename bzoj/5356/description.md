
# Description

<div class="content"><div>给定一棵树，初始时非叶节点均为无色，叶节点会是红色、蓝色或无色。小红和小蓝轮流给无色叶子染色（小红染</div>
<div>红色，小蓝染蓝色，小红先染）。所有叶子染完后，非叶节点的颜色将被逐一确定：一个非叶节点的颜色是它所有</div>
<div>儿子的颜色中出现较多的那个（保证有奇数个儿子）。最后，根是谁的颜色谁就获胜。求小红是否能赢，若能赢，</div>
<div>求出第一步选择哪些叶子能赢。</div>
<p></p></div>

# Input

<div class="content"><p>第一行一个整数t表示数据组数。</p>
<div>每组数据第一行一个整数n表示节点数。</div>
<div>第二行n个整数，第i个整数fi表示i的父亲，保证f1=0。</div>
<div>第三行n个整数，第i个整数gi表示i的初始颜色（0表示红色，1表示蓝色，-1表示无色）。</div></div>

# Output

<div class="content"><div></div>
<div>
<div>每组数据输出一行。</div>
<div>若小红能赢，先输出一个整数m表示第一步可以选的叶子数，接下来m个整数表示那些叶子的编号，从小到大输出。</div>
<div>若你只知道小红能赢，你可以只输出一行一个整数0。</div>
<div>否则输出一个整数-1。</div>
<div>t&lt;=10，n≤100000。</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2<br/>
0 1<br/>
-1 -1<br/>
2<br/>
0 1<br/>
-1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2<br/>
-1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

