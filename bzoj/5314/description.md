
# Description

<div class="content"><div>外星人又双叒叕要攻打地球了，外星母舰已经向地球航行！这一次，JYY已经联系好了黄金舰队，打算联合所有JSO</div>
<div>Ier抵御外星人的进攻。在黄金舰队就位之前，JYY打算事先了解外星人的进攻计划。现在，携带了监听设备的特工</div>
<div>已经秘密潜入了外星人的母舰，准备对外星人的通信实施监听。外星人的母舰可以看成是一棵n个节点、n-1条边的</div>
<div>无向树，树上的节点用1,2...n编号。JYY的特工已经装备了隐形模块，可以在外星人母舰中不受限制地活动，可以</div>
<div>神不知鬼不觉地在节点上安装监听设备。如果在节点u安装监听设备，则JYY能够监听与u直接相邻所有的节点的通</div>
<div>信。换言之，如果在节点u安装监听设备，则对于树中每一条边(u,v)，节点v都会被监听。特别注意放置在节点u的</div>
<div>监听设备并不监听u本身的通信，这是JYY特别为了防止外星人察觉部署的战术。</div>
<div></div>
<div>JYY的特工一共携带了k个监听设备，现在JYY想知道，有多少种不同的放置监听设备的方法，能够使得母舰上所有</div>
<div>节点的通信都被监听？为了避免浪费，每个节点至多只能安装一个监听设备，且监听设备必须被用完。</div>
<div></div></div>

# Input

<div class="content"><div>输入第一行包含两个整数n,k，表示母舰节点的数量n和监听设备的数量k。</div>
<div>接下来n-1行，每行两个整数u,v（1≤u,v≤n），表示树中的一条边。</div>
<div>1≤n≤10^5,1≤k≤min{n,100}</div>
<div></div></div>

# Output

<div class="content"><div>输出一行，表示满足条件的方案数。</div>
<div>因为答案可能很大，你只需要输出答案mod 1,000,000,007的余数即可</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
样例解释<br/>
样例数据是一条链 <br/>
1–2–3–4–5<br/>
首先，节点 2和 4必须放置监听设备，否则 1,5将无法被监听（放置的监听设备无法监听它所在的节点）。剩下一<br/>
个设备必须放置在 3号节点以同时监听 2,4因此在 2,3,4节点放置监听设备是唯一合法的方案。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

