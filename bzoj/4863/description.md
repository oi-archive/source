
# Description

<div class="content"><div>21YY年，夏。</div>
<div>时过境迁，小诚已是星际联邦（FederationofPlanets）太空防御理事会的技术顾问。去年联邦举行大选，新总统</div>
<div>刚刚宣誓就任。新政府的主要政策之一是对行政区域进行重新规划，将各个星球之间原有的行政关系精简。联邦有</div>
<div>N个星球，新的行政体系结构形如一个二叉树。联邦的行政中心为首都，其他所有星球分成至多两个区域，每个区</div>
<div>域内部又是同样的结构。在此番行政改革之前，每个星球驻扎着一支太空舰队。其中，第i个星球驻扎舰队的战斗</div>
<div>力是Fi。在行政改革的同时，太空防御理事会负责调整各个舰队的驻地，以符合军事条例中要求每个行政区域中心</div>
<div>驻扎的舰队是区域内战斗力最强舰队的规定。此外，根据军事条例，舰队调整驻地的方式只有一种，就是两个星球</div>
<div>的舰队交换驻防。现在，所有星球之间共有M条双向的星际航道。只有存在星际航道的两个星球才能进行舰队换防</div>
<div>。为了节省开支，理事会希望总的换防次数尽量少。早在年初，理事会就委托了小诚制定换防计划，但是小诚至今</div>
<div>还未完成任务。你能否帮助小诚，使他免于被解职的命运呢？</div></div>

# Input

<div class="content"><div>第一行，两个整数N,M。</div>
<div>第二行，N个整数R1,R2,…,RN，由空格隔开。Ri表示星球i的直属上级星球编号。对于联邦首都，Ri用0表示。</div>
<div>第三行，N个互不相同的整数F1,F2,…,FN，由空格隔开。其中Fi表示当前驻扎在星球i的舰队的战斗力。</div>
<div>接下来M行，每行两个整数Xi,Yi，表示在星球Xi和星球Yi之间存在一条星际航道。</div>
<div>N&lt;=12,M&lt;=20</div>
<div>1 ≤ Fi ≤ 100。 输入数据保证星球之间的行政关系形成一个二叉</div>
<div>树， 任何两个星球之间至多有一条星际航道， 且星际航道不会出现自环。 数据保证有解。</div></div>

# Output

<div class="content"><div>仅一行，一个整数，表示总换防次数的最小值。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
0 1 2 3<br/>
1 2 3 4<br/>
1 2<br/>
1 4<br/>
2 3<br/>
1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

