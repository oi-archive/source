
# Description

<div class="content"><div>小Q同学现在沉迷炉石传说不能自拔。他发现一张名为克苏恩的牌很不公平。如果你不玩炉石传说，不必担心，小Q</div>
<div>同学会告诉你所有相关的细节。炉石传说是这样的一个游戏，每个玩家拥有一个 30 点血量的英雄，并且可以用牌</div>
<div>召唤至多 7 个随从帮助玩家攻击对手，其中每个随从也拥有自己的血量和攻击力。小Q同学有很多次游戏失败都是</div>
<div>因为对手使用了克苏恩这张牌，所以他想找到一些方法来抵御克苏恩。他去求助职业炉石传说玩家椎名真白，真白</div>
<div>告诉他使用奴隶主这张牌就可以啦。如果你不明白我上面在说什么，不必担心，小Q同学会告诉你他想让你做什么</div>
<div>。现在小Q同学会给出克苏恩的攻击力是 K ，表示克苏恩会攻击 K 次，每次会从对方场上的英雄和随从中随机选</div>
<div>择一个并对其产生 1 点伤害。现在对方有一名克苏恩，你有一些奴隶主作为随从，每名奴隶主的血量是给定的。</div>
<div>如果克苏恩攻击了你的一名奴隶主，那么这名奴隶主的血量会减少 1 点，当其血量小于等于 0 时会死亡，如果受</div>
<div>到攻击后不死亡，并且你的随从数量没有达到 7 ，这名奴隶主会召唤一个拥有 3 点血量的新奴隶主作为你的随从</div>
<div>；如果克苏恩攻击了你的英雄，你的英雄会记录受到 1 点伤害。你应该注意到了，每当克苏恩进行一次攻击，你</div>
<div>场上的随从可能发生很大的变化。小Q同学为你假设了克苏恩的攻击力，你场上分别有 1 点、 2 点、 3 点血量的</div>
<div>奴隶主数量，你可以计算出你的英雄受到的总伤害的期望值是多少吗？</div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>输入包含多局游戏。</div>
<div>第一行包含一个整数 T (T&lt;100) ，表示游戏的局数。</div>
<div>每局游戏仅占一行，包含四个非负整数 K, A, B 和 C ，表示克苏恩的攻击力是 K ，你有 A 个 1 点血量的奴隶</div>
<div>主， B 个 2 点血量的奴隶主， C 个 3 点血量的奴隶主。</div>
<div>保证 K 是小于 50 的正数， A+B+C 不超过 7 。</div>
<div></div>
<div></div></div>

# Output

<div class="content"><p>对于每局游戏，输出一个数字表示总伤害的期望值，保留两位小数。</p>
<p></p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
1 1 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.25</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

