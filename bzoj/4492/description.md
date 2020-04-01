
# Description

<div class="content"><div>007发现她的最大敌人De Referenced Nullpointer博士(简称Dr. Null)的一个阴谋。Dr. Null想摧毁两个服务器的其中一个。Dr. Null正准备去实施他的方案，并且他也正在去服务器的路上。<span style="white-space:pre" class="Apple-tab-span">	</span>所以，这意味着007必须离开她正在泡着帅哥吃早饭的生活。</div>
<div>007和Dr. Null都入侵了一个卫星系统，所以他们总是知道对方的位置。卫星系统把地图表示为一个连通的无向图，而007，Dr. Null和每个服务器都位于图的节点上。两个服务器处于相邻的节点上，因为它们在一个房间里。007和Dr. Null都能在一个时间单位内走过一条边，同样他们也可以不移动。摧毁服务器也需要一个时间单位。007和Dr. Null的行动是轮流进行的。Dr. Null最先开始行动。</div>
<div>如果007抓住了Dr. Null，或者能永远阻止Dr. Null摧毁服务器，就是007胜利。007抓住Dr. Null指的是007走到了Dr. Null所在的节点上。</div>
<div>007想知道她现在能吃着早饭泡着帅哥最迟能到哪时候，也依然可以取得胜利，无论Dr. Null采取什么策略。</div>
<div>请你帮007写一个程序计算最迟出发的时间，并且保证能赢Dr. Null。</div>
<div>当007没有出发时，她不能去抓任何人，即使这时Dr. Null走到了007所处节点上。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数N和M，表示地图中节点和边的数量。节点从1到N标号，边从1到M标号。</div>
<div>第二行四个不同的整数s，d，a，b。表示007的初始位置，Dr. Null的初始位置，和两个服务器的位置。</div>
<div>下面M行描述边，每行两个整数u和v，（1&lt;=u,v&lt;=N）表示这条边连接的两个节点u,v。</div>
<p></p></div>

# Output

<div class="content"><div>包含一行一个整数，表示007最迟的出发时间，并保证能赢Dr. Null。<span style="white-space: pre;" class="Apple-tab-span">	</span>如果007必须在轮到她的第一回合就出发，输出0。</div>
<div>如果007不可能胜利，输出-1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6<br/>
1 2 3 4<br/>
1 5<br/>
5 6<br/>
6 3<br/>
6 4<br/>
1 2<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=300,000 M&lt;=600,000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

