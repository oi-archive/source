# 题目描述

<p>甲午年即将过去，新的一年即将到来。此时此刻，不由得让人想起一些童年的回忆，比如说魔塔。</p>
<p>魔塔是一种固定数值RPG游戏。下面是一张游戏截图：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/70/mt-game.png" alt="魔塔"/></p>
<p>这个游戏在一个 $n \times m$ 的棋盘上进行。行编号为 $1, \dots, n$，列编号为 $1, \dots, m$。</p>
<p>为了简单起见，我们假设这个魔塔只有一层。</p>
<p>我们用 $(x, y)$ 来表示第 $x$ 行第 $y$ 列的格子，</p>
<p>这个格子可能是空地或不可通行的墙壁，也可能有怪物，或者有宝物，或者是门。</p>
<p>玩家有以下几个属性：</p>
<ul><li>生命值 $\mathrm{HP}$，简称 “生命”。</li>
<li>攻击力 $\mathrm{ATK}$，简称 “攻击”。</li>
<li>防御力 $\mathrm{DEF}$，简称 “防御”。</li>
<li>魔法防御力 $\mathrm{INT}$，简称 “魔防”。</li>
</ul><p>在任意时刻，玩家的属性都满足 $\mathrm{HP} &gt; 0$, $\mathrm{ATK} \ge 0$, $\mathrm{DEF} \ge 0$, $\mathrm{INT} \ge 0$，且这些属性都是整数。</p>
<p>每一种怪物也有以下属性：</p>
<ul><li>生命值 $\mathrm{HP}$</li>
<li>攻击力 $\mathrm{ATK}$</li>
<li>防御力 $\mathrm{DEF}$</li>
</ul><p>这些属性也都是整数且 $\mathrm{HP} &gt; 0$, $\mathrm{ATK} \ge 0$, $\mathrm{DEF} \ge 0$。</p>
<p>玩家与一只怪物战斗时，首先玩家的 $\mathrm{HP}$ 会加上玩家的魔防的值，然后玩家作为攻击方，怪物作为防御方。</p>
<p>攻击方的生命值记为 $\mathrm{HP}_0$，攻击力记为 $\mathrm{ATK}_0$，防御力记为 $\mathrm{DEF}_0$，</p>
<p>防御方的生命值记为 $\mathrm{HP}_1$，攻击力记为 $\mathrm{ATK}_1$，防御力记为 $\mathrm{DEF}_1$。</p>
<pre><code class="sh_cpp">while (true)
{
    damage = max(0, ATK_0 - DEF_1)
    HP_1 = HP_1 - damage
    if (HP_1 &lt;= 0)
        break
    else
        交换攻击方和防御方
}</code></pre>
<p>这段伪代码的意思是，每个回合防御方受到“攻击方攻击力”减“防御方防御力”的伤害（小于等于 $0$ 则不会受到伤害），然后如果双方 $\mathrm{HP}$ 都大于 $0$ 则交换攻击方和防御方，否则战斗结束。</p>
<p>这时如果玩家的 $\mathrm{HP} \le 0$，则游戏结束。否则玩家的 $\mathrm{HP} = \min(\mathrm{HP}, \text{战斗开始前玩家的 HP})$。</p>
<p>有些怪物还有一个或两个特殊属性值 $p, q$：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>$p$ 或 $q$ 的值</th>
<th>属性名称</th>
<th>属性效果</th>
</tr></thead><tbody><tr><td>$0$</td><td>普通</td><td>无</td></tr><tr><td>$8$</td><td>坚固</td><td>玩家每回合对怪物造成最多 $1\mathrm{HP}$ 的伤害（即每回合在原本对怪的伤害和 $1$ 之间取最小值作为伤害）</td></tr><tr><td>$16$</td><td>先攻</td><td>第一个回合前，怪物先对玩家攻击一次</td></tr><tr><td>$64$</td><td>魔攻</td><td>怪物的攻击无视玩家的防御（即把玩家的 $\mathrm{DEF}$ 视为 $0$）</td></tr><tr><td>$-x$</td><td>连击</td><td>怪物每回合攻击 $x$ 次 （$x&gt;1$）</td></tr></tbody></table></div>

<p>保证 $p$ 和 $q$ 都不等于 $0$ 时，$p$, $q$ 表示不同的属性，且不会有一种怪物同时有连击和先攻的属性。</p>
<p>宝物分为以下几种：</p>
<ul><li>血瓶：增加一定生命值</li>
<li>红宝石：增加一定攻击力</li>
<li>蓝宝石：增加一定防御力</li>
<li>绿宝石：增加一定魔防</li>
<li>钥匙：可以用来开门，开一扇门消耗一把钥匙，其中黄钥匙能开黄门，蓝钥匙能开蓝门，红钥匙能开红门。</li>
</ul><p>玩家从某个位置开始游戏，每次移动只能走到相邻（有公共边）且不是墙壁的格子上。</p>
<ul><li>如果这个格子上有怪物，则玩家与这只怪物战斗。</li>
<li>如果这个格子上有宝物，则玩家获得这个宝物。</li>
<li>如果这个格子是门，则玩家使用相应的钥匙开门。</li>
</ul><p>以上事件结束后，该格子变为空地。</p>
<p>给定玩家的初始状态（位置，$\mathrm{HP}$，$\mathrm{ATK}$，$\mathrm{DEF}$，$\mathrm{INT}$，各种钥匙的数量）和目标状态，要求给出一种玩法，使玩家能达到目标状态的位置且各项属性和钥匙的数量都<strong>不小于</strong>目标状态的属性和钥匙的数量。在这个条件下，玩家的 $\mathrm{HP}$ 越大越好。</p>

# 输入格式


<p>该题为提交答案型试题，所有输入数据 tower1.in ~ tower10.in 见数据下载。</p>
<p>第一行两个正整数 $n, m$。</p>
<p>接下来四行分别是每种血瓶、红宝石、蓝宝石、绿宝石增加的属性值，</p>
<p>每行第一个非负整数 $k$ 表示这种宝物的种类数，接下来 $k$ 个整数，第 $i$ 个整数表示第 $i$ 种这样的宝物增加的属性值。</p>
<p>接下来一行一个正整数 $m_c$，表示一共有 $m_c$ 种怪物。</p>
<p>接下来 $m_c$ 行，每行五个整数 $H_i$, $A_i$, $D_i$, $p_i$, $q_i$，分别表示第 $i$ 种怪物的 $\mathrm{HP}$, $\mathrm{ATK}$, $\mathrm{DEF}$, $p$, $q$。</p>
<p>接下来 $n$ 行，每行 $m$ 个整数，第 $i$ 行第 $j$ 列的数表示 $(i, j)$ 这个格子，设这个数为 $v$：</p>
<ul><li>如果 $v = 0$，则 $(i, j)$ 是一块空地。</li>
<li>如果 $v = 1$，则 $(i, j)$ 是一堵墙壁。</li>
<li>如果 $11 \le v \le 13$，则 $(i, j)$ 上有一把钥匙，其中 $v = 11$ 为黄钥匙，$v = 12$ 为蓝钥匙，$v = 13$ 为红钥匙。</li>
<li>如果 $21 \le v \le 23$，则 $(i, j)$ 是一扇门，其中 $v = 21$ 为黄门，$v = 22$ 为蓝门，$v = 23$ 为红门。</li>
<li>如果 $100 &lt; v &lt; 200$，则 $(i, j)$ 上有一个第 $v - 100$ 种的血瓶。</li>
<li>如果 $200 &lt; v &lt; 300$，则 $(i, j)$ 上有一个第 $v - 200$ 种的红宝石。</li>
<li>如果 $300 &lt; v &lt; 400$，则 $(i, j)$ 上有一个第 $v - 300$ 种的蓝宝石。</li>
<li>如果 $400 &lt; v &lt; 500$，则 $(i, j)$ 上有一个第 $v - 400$ 种的绿宝石。</li>
<li>如果 $500 &lt; v$，则 $(i, j)$ 上有一只第 $v - 500$ 种的怪物。</li>
</ul><p>接下来一行九个整数 $x, y, \mathrm{HP}, \mathrm{ATK}, \mathrm{DEF}, \mathrm{INT}, \mathrm{key}_1, \mathrm{key}_2, \mathrm{key}_3$，表示初始状态的位置、各项属性和各种钥匙的个数。</p>
<p>接下来一行九个整数 $x, y, \mathrm{HP}, \mathrm{ATK}, \mathrm{DEF}, \mathrm{INT}, \mathrm{key}_1, \mathrm{key}_2, \mathrm{key}_3$，表示目标状态的位置、各项属性和各种钥匙的个数。</p>
<p>不保证输入中的所有宝物和怪物都会在地图中出现，但是保证地图上至少有一只怪物。</p>
<p><strong>请注意比赛中途提交上去后，对于每个测试点如果有分就会显示该测试点满分，比赛完后会进行重测给出真实的分数，请特别注意！</strong></p>

# 输出格式


<p>针对给定的 10 个输入文件 tower1.in ~ tower10.in，你需要分别提交你的输出文件 tower1.out ~ tower10.out。</p>
<p>第一行一个整数 $q$，表示你的玩法中操作的次数。$q$ 要满足 $0 \le q \le 10^6$。</p>
<p>接下来 $q$ 行，每行两个整数 $x, y$，表示这次操作你走到了 $(x, y)$ 位置，如果 $(x, y)$ 位置不是空地则会触发相应的事件。你需要保证从上次的位置能只经过空地格子走到 $(x, y)$。</p>
<p>如果最后不在目标状态的位置，玩家的人物会自动走到目标状态的位置。同样，如果不是空地则会触发事件，你需要保证从上次的位置能只经过空地格子走到目标状态位置。</p>
<p><strong>请注意比赛中途提交上去后，对于每个测试点如果有分就会显示该测试点满分，比赛完后会进行重测给出真实的分数，请特别注意！（很重要所以说两遍）</strong></p>

# 样例一


<h4>input</h4>
<pre>4 5
0
1 2
1 2
0
3
50 20 0 0 0
60 22 1 0 0
70 25 1 0 0
0 0 0 0 0
1 1 503 1 1
301 501 0 502 201
1 1 0 1 1
4 3 200 10 10 0 0 0 0
1 3 1 12 12 0 0 0 0

</pre>

<h4>output</h4>
<pre>5
3 2
3 1
3 4
3 5
2 3

</pre>

<h4>explanation</h4>
<p>这个样例玩家的玩法如下：</p>
<p>一开始的属性为 $\mathrm{HP} = 200$，$\mathrm{ATK} = 10$，$\mathrm{DEF} = 10$。</p>
<p>走到 $(3, 2)$，杀死一只第一种类型的怪物，状态变为 $\mathrm{HP} = 160$，$\mathrm{ATK} = 10$，$\mathrm{DEF} = 10$。</p>
<p>走到 $(3, 1)$，得到一个蓝宝石，状态变为 $\mathrm{HP} = 160$，$\mathrm{ATK} = 10$，$\mathrm{DEF} = 12$。</p>
<p>走到 $(3, 4)$，杀死一只第二种类型的怪物，状态变为 $\mathrm{HP} = 100$，$\mathrm{ATK} = 10$，$\mathrm{DEF} = 12$。</p>
<p>走到 $(3, 5)$，得到一个红宝石，状态变为 $\mathrm{HP} = 160$，$\mathrm{ATK} = 12$，$\mathrm{DEF} = 12$。</p>
<p>走到 $(2, 3)$，杀死一只第三种类型的怪物，状态变为 $\mathrm{HP} = 22$，$\mathrm{ATK} = 12$，$\mathrm{DEF} = 12$。</p>
<p>最后走到 $(1, 3)$，达到目标状态，最终的 $\mathrm{HP}$ 值为 $22$。</p>

# 评分方式


<p>对每组数据，我们设置了 $3$ 个参数 $H_{10}$, $H_7$, $H_5$。</p>
<p>如果你的输出不合法（如走到不能走到的格子上，或 $\mathrm{HP} \le 0$ 即玩家死亡）或没有打败任何一只怪物，得 $0$ 分。</p>
<p>如果最后玩家的人物在自动走到目标状态的位置的过程中出错，比如根本无法到达目标位置，被怪打死等，或者未能达到目标状态的其它参数要求，而其余部分均合法则得 $1$ 分。</p>
<p>否则，设你最后 $\mathrm{HP}$ 值为$H_u$：</p>
<ul><li>若 $H_u \ge H_{10}$，得 $10$ 分，</li>
<li>若 $H_{10} &gt; H_u \ge H_7$，得 $7$ 分，</li>
<li>若 $H_7 &gt; H_u \ge H_5$，得 $5$ 分，</li>
<li>若 $H_5 &gt; H_u$，得 $3$ 分。</li>
</ul><p><strong>请注意比赛中途提交上去后，对于每个测试点如果有分就会显示该测试点满分，比赛完后会进行重测给出真实的分数，请特别注意！（很重要所以说三遍）</strong></p>

# 如何测试你的输出


<p>在终端中先切换到该试题的目录下：（windows用户请使用cmd）（假设你把输入输出文件、checker什么的都放在了tower这个文件夹下）</p>
<p><code>cd tower</code></p>
<p>我们提供checker这个工具来测试你的输出文件是否是可接受的。使用这个工具的方法是，在终端中运行</p>
<p><code>./checker_linux64 &lt;case_no&gt;</code></p>
<p>其中<code>case_no</code>是测试数据的编号。例如</p>
<p><code>./checker_linux64 3</code></p>
<p>将测试tower3.out是否可以接受。（windows用户请使用<code>checker_win32 3</code>）（什么你是windows 64位？放心吧可以运行win32应用程序的。）</p>
<p>当然我们有对应的linux 32位版本：<code>checker_linux32</code>。如果linux用户发现无法运行程序，请尝试执行<code>chmod +x checker_linux64</code>或<code>chmod +x checker_linux32</code>后重试。</p>
<p>其它操作系统请安装 <a href="//nodejs.org/">node.js</a> 然后使用 <code>node checker.js &lt;case_no&gt;</code> 运行checker。</p>
<p>在你调用这个程序后，checker将根据你给出的输出文件给出测试的结果。</p>
<h4>windows小白特别篇</h4>
<p>首先你要下载数据和checker并解压，放在某个文件夹下。比如 D:\wahaha\tower。</p>
<p>然后你需要打开 cmd。如果是XP，点击开始，运行，然后打 cmd 三个字，然后确定，cmd 就出来了。如果是其它的 windows，实在找不到就用windows的搜索功能找，还找不到就上网搜一下“cmd在哪里”。</p>
<p>好，打开了之后默认位置应该在 C 盘，如果你下载的数据和checker放在了C盘那不要紧，如果放在了D盘请在cmd中输入</p>
<p><code>D:</code></p>
<p>然后回车，来切换所在盘。</p>
<p>然后再 <code>cd D:\wahaha\tower</code> 来切换所在目录。</p>
<p>接下来的事情就如前所述了。</p>
<p>听说有人用记事本打开输入文件后发现是一堆乱码？由于linux下换行符跟windows下不同，请使用其它编辑器，比如GUIDE、Dev-C++、写字板、vim、Emacs等打开。</p>
<h4>linux小白特别篇</h4>
<p>感觉应该没有不会用终端的linux选手。</p>
<p>linux的文件分为可读，可写，可执行三种，下载下来的文件一般并不是可执行的，这就是为什么之前我们要 <code>chmod +x checker_linux64</code>，这是赋予这个文件可执行的权限。请注意这只是赋予可执行权限而不是执行这个文件，不要搞错意思了。</p>
<p>然后就可以开心地玩耍啦！</p>
<h4>我还是不会用！</h4>
<p>参见 FAQ 里我们的联系方式。</p>
<p><strong>请注意比赛中途提交上去后，对于每个测试点如果有分就会显示该测试点满分，比赛完后会进行重测给出真实的分数，请特别注意！（我写了四遍，如果你还看不见我就给你跪了）</strong></p>

# 来源


<p>UOJ Goodbye Jiawu</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=70">输入数据及checker下载</a></p>
