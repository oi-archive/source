# 

 
 # 题目描述 
<p>
小H最近沉迷于一个魔兽rpg对战地图Defense of the Ancients。他对dota的字幕提示非常感兴趣，因此想要编写一个程序来实现类似功能。<br>Dota的字幕提示主要是关于杀人，主要有以下4类提示：<br>基本类：A pawned B’s head.<br>连杀类：A is on a killing spree/dominating/has a mega kill……!<br>多杀类：A just got a Double Kill/Triple Kill!<br>局势类：The Scourge/Sentinel is OWNING!<br>关于Dota的四类字幕提示，出现规律分别如下：<br><br>基本类：<br>这类一定在每次击杀后第一时间出现。<br>	这类提示有以下3个变化：<br>1.	如果这是全游戏第一个有效击杀，那么在下一行显示“A just drew first blood.”<br>2.	如果在一个有效击杀内被杀的玩家在之前有连杀类提示，则显示“A has just ended B’s [B的称号].”其中括号内为B的当前称号<br>3.	如果是一名玩家杀死了他自己，则显示“A has killed himself.”，如果一个玩家不是被敌方阵营玩家杀死，则显示“A has been killed by B.”<br>连杀类：<br>这类提示出现在基本类之后，如果某人在没有被敌对阵营玩家杀死的前提下完成了至少3次击杀，那么从此往后每次击杀都会有连杀类提示，字幕分别如下：<br>3杀 - A is on a killing spree!<br>4杀 - A is dominating!<br>5杀 - A has a mega kill!<br>6杀 - A is unstoppable!<br>7杀 - A is wicked sick!<br>8杀 - A has a monster kill!<br>9杀 - A is godlike!<br>10杀以上 - A is beyond godlike. someone kill him!<br>同时当该玩家在之后被杀死时基本类提示会出现变化，出现提示与该玩家的称号有关，称号分别如下：<br>3杀 - killing spree<br>4杀 - dominating<br>5杀 - mega kill<br>6杀 - unstoppable<br>7杀 - wicked sick<br>8杀 - monster kill<br>9杀 - godlike<br>10杀以上 - beyond godlike<br>多杀类：<br>这类提示出现在连杀类提示之后，如果某人在杀死一个人之后10秒内完成了第二	次击杀，则出现多杀类提示，字幕分别如下：<br>	双杀：A just got a Double Kill!<br>	三杀：A just got a Triple Kill!<br>多杀统计只需要相邻两次击杀时间相差不超过10秒，即三杀以上的第一次击杀和最后一次击杀之间相差可以超过10秒。<br>	注意当多杀累计超过3个时，仍然显示三杀提示。<br>	另外多杀与连杀为两个系统，即多杀期间即使自身死亡也不中断多杀统计。<br>局势类：<br>	这类提示出现在多杀类提示之后。<br>	如果一个阵营内的玩家完成了至少5次击杀并且此间本阵营玩家没有被敌对阵营玩家击杀，则会显示：<br>	The Scourge/Sentinel is OWNING!<br>	这里与击杀方阵营有关。<br>需要注意的是，一个击杀为有效击杀当且仅当这个击杀是一名玩家被另一名玩家所杀，若一个击杀并非有效击杀，则只会触发基本类提示。<br><br></p> 

 
 # 输入格式 
<p>
输入文件的第一行为整场游戏的玩家个数N。<br>接下来N行，每行首先是一个玩家的名字，名字仅包含大写字母、小写字母以及数字，长度不超过15个字符，紧接着一个数字表示该玩家阵营，如果是0表示是Sentinel方，1表示是Scourge方，阵营数字只可能是0或者1。<br>接下来一行为游戏的击杀的总次数M。<br>接下来M行每行描述一次击杀，形如aa:bb A is killed by B，即在aa分bb秒时A被B杀死了，击杀叙述顺序保证在时间上是不减的。<br>输入文件保证合法，即不会出现某玩家杀死同阵营另一玩家，并且被击杀者一定是一名玩家。<br>整场比赛不超过60分钟<br></p> 

 
 # 输出格式 
<p>
输出文件包含若干行，为要求的dota字幕提示。<br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3
YourLittleSiste 0
Ehero 0
Tra 1
21
01:00 Ehero is killed by Tra
02:00 Ehero is killed by Tra
03:00 Ehero is killed by Tra
04:00 Ehero is killed by Tra
04:05 Tra is killed by Roshan
12:00 Tra is killed by Dragon
15:00 Tra is killed by Tra
20:00 Tra is killed by YourLittleSiste
20:01 Tra is killed by YourLittleSiste
20:02 Tra is killed by YourLittleSiste
20:03 Tra is killed by YourLittleSiste
20:04 Tra is killed by YourLittleSiste
25:00 Tra is killed by YourLittleSiste
26:00 Tra is killed by YourLittleSiste
27:00 Tra is killed by YourLittleSiste
28:00 Tra is killed by YourLittleSiste
29:00 Tra is killed by YourLittleSiste
32:00 YourLittleSiste is killed by YourLittleSiste
34:59 YourLittleSiste is killed by Tra
34:59 Tra is killed by YourLittleSiste
35:09 Ehero is killed by Tra


</td><td>Tra pawned Ehero's head.
Tra just drew first blood.
Tra pawned Ehero's head.
Tra pawned Ehero's head.
Tra is on a killing spree!
Tra pawned Ehero's head.
Tra is dominating!
Tra has been killed by Roshan.
Tra has been killed by Dragon.
Tra has killed himself.
YourLittleSiste has just ended Tra's dominating.
YourLittleSiste pawned Tra's head.
YourLittleSiste just got a Double Kill!
YourLittleSiste pawned Tra's head.
YourLittleSiste is on a killing spree!
YourLittleSiste just got a Triple Kill!
YourLittleSiste pawned Tra's head.
YourLittleSiste is dominating!
YourLittleSiste just got a Triple Kill!
YourLittleSiste pawned Tra's head.
YourLittleSiste has a mega kill!
YourLittleSiste just got a Triple Kill!
The Sentinel is OWNING!
YourLittleSiste pawned Tra's head.
YourLittleSiste is unstoppable!
The Sentinel is OWNING!
YourLittleSiste pawned Tra's head.
YourLittleSiste is wicked sick!
The Sentinel is OWNING!
YourLittleSiste pawned Tra's head.
YourLittleSiste has a monster kill!
The Sentinel is OWNING!
YourLittleSiste pawned Tra's head.
YourLittleSiste is godlike!
The Sentinel is OWNING!
YourLittleSiste pawned Tra's head.
YourLittleSiste is beyond godlike. someone kill him!
The Sentinel is OWNING!
YourLittleSiste has killed himself.
Tra has just ended YourLittleSiste's beyond godlike.
YourLittleSiste pawned Tra's head.
Tra pawned Ehero's head.
Tra just got a Double Kill!

对于100%的数据，N ≤ 20 000，M ≤ 500 00。
   为方便处理，本题中的字幕提示系统与真实dota略有不同，分歧处以题面为准。
   对于同一秒发生的击杀，以在输入文件中先出现的击杀为先发生。
   严格注意题目叙述中大小写的区别，注意输出文件行末不要有空格。</td></tr></table>
