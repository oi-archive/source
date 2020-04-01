
# Description

<div class="content"><div>有一个园子，里面有n个草丛排成一排，标号1~n，有一个袋鼠，从s出发，每次跳一步跳到一个其他的草丛，经过</div>
<div>每个草丛恰好一次，最终到达t。显然他会跳跃n-1次为了不被人类发现，袋鼠每次跳跃的方向必须与前一次不同，</div>
<div>具体地，如果他现在在now,他是从prev跳跃一次到达now的，然后他跳跃一次到达next，那么如果prev&lt;now，就必</div>
<div>须有now&lt;next，如果now&lt;prev，就必须有next&lt;now问从s到t的方案数，模1e9+7两个路线不同，当且仅当草丛被访</div>
<div>问的顺序不同保证至少有一种方案初始时可以往任意方向跳。</div>
<div><span style="color: rgb(255, 0, 0);">修正下：<span style="font-family: arial, verdana, helvetica, sans-serif;">那么如果prev&lt;now，就必须有next&lt;now</span></span></div>
<p><span style="color: rgb(255, 0, 0);"><span style="font-family: arial, verdana, helvetica, sans-serif;">如果now&lt;prev,就必须有now&lt;next</span></span></p></div>

# Input

<div class="content"><p> 一行三个整数，n，s，t</p>
<div>2&lt;=n&lt;=2000</div>
<div>1&lt;=s&lt;=n</div>
<div>1&lt;=t&lt;=n</div></div>

# Output

<div class="content"><p> 一行一个整数，代表答案</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢alone_wolf提供翻译">鸣谢alone_wolf提供翻译</a></p></div>

