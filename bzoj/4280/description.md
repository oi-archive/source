
# Description

<div class="content"><div>在一条笔直的道路上从左到右一共有n片区域，每一片区域一开始都种着一棵树，其中第i片区域种着高度为h[i]的树。接下来你需要处理q个操作：</div>
<div>1 l r c ： 将第l片区域到第r片区域内的所有树的高度拔高c(|c|&lt;=500)个单位。</div>
<div>2 l r h ： 将一把刀固定在高度为h(1&lt;=h&lt;=10^9)的空中，对第l片区域到第r片区域内的所有树进行砍伐。</div>
<div>3 l r h ： 往第l片区域到第r片区域内的每个区域种上一棵高度为h(1&lt;=h&lt;=10^9)的树。</div>
<div>4 l r   ： 查询第l片区域到第r片区域内最高的树的高度。</div>
<div>注意：本题中的高度为相对于某个水平面的高度，也就是说可能会有负数的出现。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数n,q(1&lt;=n,q&lt;=500000)，分别表示区域数和操作数。</div>
<div>第二行包含n个正整数，其中第i个数表示h[i](1&lt;=h[i]&lt;=10^9)。</div>
<div>接下来q行依次描述每一个操作。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出若干行，每行一个整数，对于每次查询输出相应的结果。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 5<br/>
3 7<br/>
4 1 2<br/>
1 1 2 1<br/>
4 1 2<br/>
3 1 1 5<br/>
4 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
8<br/>
8<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

