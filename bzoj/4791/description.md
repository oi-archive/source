
# Description

<div class="content"><div>俄罗斯套娃是一些尺寸递增的木制雕像，它们可以嵌套在一起。每个套娃可以放进一个更大的套娃，也可以被放入</div>
<div>一个更小的套娃。每个套娃内部最多只能直接嵌套一个套娃，但是那个套娃内部还可以继续嵌套。给定n个尺寸互</div>
<div>不相同的套娃，按尺寸从小到大依次编号为1到n。如果套娃a被直接嵌入套娃b，那么我们称b是a的父亲，如果一个</div>
<div>套娃没有父亲，那么我们称它是自由的。一组镶嵌方案可以用每个套娃的父亲来表示。我们可以每步可以做以下两</div>
<div>种操作中的任意一种：</div>
<div></div>
<div>1.把一个自由的套娃直接嵌入一个更大的没有被放入东西的套娃。</div>
<div></div>
<div>2.选择一个不自由的套娃，将其从其父亲中取出。</div>
<div></div>
<div>给定初始局面，请计算达到目标局面的最小的操作步数。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=100000)，表示套娃的个数。</div>
<div>第二行包含n个整数p_1,p_2,...,p_n(0&lt;=p_i&lt;=n)，依次表示初始局面中每个套娃的父亲，0表示自由套娃。</div>
<div>第三行包含n个整数q_1,q_2,...,q_n(0&lt;=q_i&lt;=n)，依次表示目标局面中每个套娃的父亲，0表示自由套娃。</div>
<div>输入数据保证初始局面和目标局面均合法。</div></div>

# Output

<div class="content"><div>输出一行一个整数，即最小操作步数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
3 5 4 0 7 0 0<br/>
3 5 0 6 7 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

