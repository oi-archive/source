
# Description

<div class="content">小H最近沉迷于一个魔兽rpg对战地图Defense of the Ancients。他对dota的字幕提示非常感兴趣，因此想要编写一个程序来实现类似功能。
Dota的字幕提示主要是关于杀人，主要有以下4类提示：
基本类：A pawned B’s head.
连杀类：A is on a killing spree/dominating/has a mega kill……!
多杀类：A just got a Double Kill/Triple Kill!
局势类：The Scourge/Sentinel is OWNING!
关于Dota的四类字幕提示，出现规律分别如下：

基本类：
这类一定在每次击杀后第一时间出现。
	这类提示有以下3个变化：
1.	如果这是全游戏第一个有效击杀，那么在下一行显示“A just drew first blood.”
2.	如果在一个有效击杀内被杀的玩家在之前有连杀类提示，则显示“A has just ended B’s [B的称号].”其中括号内为B的当前称号
3.	如果是一名玩家杀死了他自己，则显示“A has killed himself.”，如果一个玩家不是被敌方阵营玩家杀死，则显示“A has been killed by B.”
连杀类：
这类提示出现在基本类之后，如果某人在没有被敌对阵营玩家杀死的前提下完成了至少3次击杀，那么从此往后每次击杀都会有连杀类提示，字幕分别如下：
3杀 - A is on a killing spree!
4杀 - A is dominating!
5杀 - A has a mega kill!
6杀 - A is unstoppable!
7杀 - A is wicked sick!
8杀 - A has a monster kill!
9杀 - A is godlike!
10杀以上 - A is beyond godlike. someone kill him!
同时当该玩家在之后被杀死时基本类提示会出现变化，出现提示与该玩家的称号有关，称号分别如下：
3杀 - killing spree
4杀 - dominating
5杀 - mega kill
6杀 - unstoppable
7杀 - wicked sick
8杀 - monster kill
9杀 - godlike
10杀以上 - beyond godlike
多杀类：
这类提示出现在连杀类提示之后，如果某人在杀死一个人之后10秒内完成了第二	次击杀，则出现多杀类提示，字幕分别如下：
	双杀：A just got a Double Kill!
	三杀：A just got a Triple Kill!
多杀统计只需要相邻两次击杀时间相差不超过10秒，即三杀以上的第一次击杀和最后一次击杀之间相差可以超过10秒。
	注意当多杀累计超过3个时，仍然显示三杀提示。
	另外多杀与连杀为两个系统，即多杀期间即使自身死亡也不中断多杀统计。
局势类：
	这类提示出现在多杀类提示之后。
	如果一个阵营内的玩家完成了至少5次击杀并且此间本阵营玩家没有被敌对阵营玩家击杀，则会显示：
	The Scourge/Sentinel is OWNING!
	这里与击杀方阵营有关。
需要注意的是，一个击杀为有效击杀当且仅当这个击杀是一名玩家被另一名玩家所杀，若一个击杀并非有效击杀，则只会触发基本类提示。

</div>

# Input

<div class="content">输入文件的第一行为整场游戏的玩家个数N。
接下来N行，每行首先是一个玩家的名字，名字仅包含大写字母、小写字母以及数字，长度不超过15个字符，紧接着一个数字表示该玩家阵营，如果是0表示是Sentinel方，1表示是Scourge方，阵营数字只可能是0或者1。
接下来一行为游戏的击杀的总次数M。
接下来M行每行描述一次击杀，形如aa:bb A is killed by B，即在aa分bb秒时A被B杀死了，击杀叙述顺序保证在时间上是不减的。
输入文件保证合法，即不会出现某玩家杀死同阵营另一玩家，并且被击杀者一定是一名玩家。
整场比赛不超过60分钟
</div>

# Output

<div class="content">输出文件包含若干行，为要求的dota字幕提示。
</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
YourLittleSiste 0<br/>
Ehero 0<br/>
Tra 1<br/>
21<br/>
01:00 Ehero is killed by Tra<br/>
02:00 Ehero is killed by Tra<br/>
03:00 Ehero is killed by Tra<br/>
04:00 Ehero is killed by Tra<br/>
04:05 Tra is killed by Roshan<br/>
12:00 Tra is killed by Dragon<br/>
15:00 Tra is killed by Tra<br/>
20:00 Tra is killed by YourLittleSiste<br/>
20:01 Tra is killed by YourLittleSiste<br/>
20:02 Tra is killed by YourLittleSiste<br/>
20:03 Tra is killed by YourLittleSiste<br/>
20:04 Tra is killed by YourLittleSiste<br/>
25:00 Tra is killed by YourLittleSiste<br/>
26:00 Tra is killed by YourLittleSiste<br/>
27:00 Tra is killed by YourLittleSiste<br/>
28:00 Tra is killed by YourLittleSiste<br/>
29:00 Tra is killed by YourLittleSiste<br/>
32:00 YourLittleSiste is killed by YourLittleSiste<br/>
34:59 YourLittleSiste is killed by Tra<br/>
34:59 Tra is killed by YourLittleSiste<br/>
35:09 Ehero is killed by Tra<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Tra pawned Ehero&#39;s head.<br/>
Tra just drew first blood.<br/>
Tra pawned Ehero&#39;s head.<br/>
Tra pawned Ehero&#39;s head.<br/>
Tra is on a killing spree!<br/>
Tra pawned Ehero&#39;s head.<br/>
Tra is dominating!<br/>
Tra has been killed by Roshan.<br/>
Tra has been killed by Dragon.<br/>
Tra has killed himself.<br/>
YourLittleSiste has just ended Tra&#39;s dominating.<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste just got a Double Kill!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste is on a killing spree!<br/>
YourLittleSiste just got a Triple Kill!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste is dominating!<br/>
YourLittleSiste just got a Triple Kill!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste has a mega kill!<br/>
YourLittleSiste just got a Triple Kill!<br/>
The Sentinel is OWNING!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste is unstoppable!<br/>
The Sentinel is OWNING!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste is wicked sick!<br/>
The Sentinel is OWNING!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste has a monster kill!<br/>
The Sentinel is OWNING!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste is godlike!<br/>
The Sentinel is OWNING!<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
YourLittleSiste is beyond godlike. someone kill him!<br/>
The Sentinel is OWNING!<br/>
YourLittleSiste has killed himself.<br/>
Tra has just ended YourLittleSiste&#39;s beyond godlike.<br/>
YourLittleSiste pawned Tra&#39;s head.<br/>
Tra pawned Ehero&#39;s head.<br/>
Tra just got a Double Kill!<br/>
<br/>
对于100%的数据，N ≤ 20 000，M ≤ 500 00。<br/>
   为方便处理，本题中的字幕提示系统与真实dota略有不同，分歧处以题面为准。<br/>
   对于同一秒发生的击杀，以在输入文件中先出现的击杀为先发生。<br/>
   严格注意题目叙述中大小写的区别，注意输出文件行末不要有空格。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

