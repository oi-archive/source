
# Description

<div class="content"><div>「不知从何处，流淌出令人熟悉的旋律。</div>
<div>我到底是在哪里，听过这个旋律？」</div>
<div>——「『囚人的旋律』，是加入了诅咒的旋律哦」</div>
<div>【问题描述】</div>
<div>被诅咒的监狱里流淌着囚人们的歌谣。</div>
<div>将罪恶的青春全部抹杀殆尽。</div>
<div>“看守”执掌“囚犯”的生杀大权。</div>
<div>“囚犯”中藏着可以杀掉“看守”的恶魔。</div>
<div>这就是，将人性扭曲的，“监狱游戏”。</div>
<div></div>
<div>监狱游戏的参加者被分为了看守和囚犯，两侧各n人。举行监狱游戏的地点在一个被改造过了的大仓库一样的地方</div>
<div>，里面有两排共2n个房间，服务入口侧的是囚犯的房间，行刑室侧的是看守的房间。如下图所示。</div>
<div> <img src="/source/bzoj/4715/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYxMS9hYS5wbmc=.png" width="459" height="278" alt=""/></div>
<div>相邻的看守与囚犯的房间之间可以通过对讲机互相沟通，但是声音会被处理，无法辨别。两侧的分类房中都有一排</div>
<div>各n扇门，从左到右编号为1～n。进入一扇门之后会有一条狭长、黑暗，而且弯弯曲曲的走廊通向房间。由于其特</div>
<div>殊的构造，看守的i号门对应房间未必就是囚犯的i号门对应的房间。因此，想在这个监狱游戏中胜出，了解门与门</div>
<div>之间的对应关系是很有必要的。接下来的问题就和监狱游戏没有太多关系了。我们令a[i]表示看守的第i扇门对应</div>
<div>囚犯的哪一扇门。令图G为有n个节点的图，编号为1～n。对于满足1≤i&lt;j≤n的一对i和j，如果有a[i]&gt;a[j]，那么</div>
<div>在G中编号为i和j的节点之间连一条边。得到的图G被称为逆序图。对于图G=(V,E)，非空点集S∈V是一个独立集当</div>
<div>且仅当对于任意两个点u,v∈V，不存在(u,v)∈E。而S是一个覆盖集当且仅当对于任意点v?S存在点u∈S满足(u,v)</div>
<div>∈E。我们在意的是，图G中有多少个点集既是独立集又是覆盖集。出于某种不知名的原因，被迫参加监狱游戏的大</div>
<div>家的安危和这个问题的答案有关。拜托了，请一定要求出这个方案数。</div>
<p></p></div>

# Input

<div class="content"><div>输入第一行含有两个整数n和m，表示逆序图的点数和边数。</div>
<div>接下来m行，每行描述一条边。每行包含两个1～n的整数，代表边的两个端点。保证没有重边和自环。</div>
<div>保证给定的图是一个合法的逆序图，即，存在至少一个序列，按照题目描述中所述方法得到的逆序图是给定的图。</div>
<div>n≤1000，0≤m≤(n(n-1))/2</div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数，表示方案数对1,000,000,007取模得到的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
2 4<br/>
2 5<br/>
1 4<br/>
3 4<br/>
3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

