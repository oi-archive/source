
# Content

《三国杀》是一款热门的桌上游戏，融合了西方类似游戏的特点，并结合中国三国时期背景，以身份为线索，以卡牌为形式，集合历史、文学、美术等元素于一身。

相信很多人都玩过这款游戏，在此只对此问题做简单介绍：
* `【杀】`<br/>
出牌阶段，攻击范围内对除自己以外的一名角色使用，效果是对该角色造成$1$点伤害。<br/>
攻击范围是$1$。（当计算距离 $D\leq 1$ 时，可以使用`【杀】`）
*`【马】`<br/>
  1. `- Num 【马】`<br/>
    当该角色出`【杀】`计算与其他角色的距离时，始终$- Num$。（可以理解为一种进攻上的优势）。
  2. `+ Num 【马】`<br/>
    当其他角色出`【杀】`计算与该角色距离时，始终$+ Num$。（可以理解为一种防御上的优势）。
  3. 一角色最多装备一匹`- Num1【马】` 和 最多一匹 `+ Num2 【马】`，可同时装备两种马。此处$Num\_1$与$Num\_2$无关

由于《三国杀》理论上来说是可以没有人数限制的，所以你叫了$N$个人一起来玩，大家坐成了一圈，逆时针依次编号$1$到$N$，现给出$M$个操作，每个操作是以下两种之一：
1. `N1 S Num`——表示编号为$N\_1$的玩家将要装备或替换一张`【马】`。<br/>$S$ 为 `+` 或 `-` 
2.  `K A B` ——表示$A$对$B$使用一张`【杀】`询问$A$能否杀到$B$ 。<br/>能则输出`Yes!` ，否则输出`I'm sorry.` 。

如图，赵云装备有一张`+1【马】`。

![title](/source/lutece/san-guo-sha/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzAxLzIwMTQwNDA5MjE0NTI0ODU5Ni5qcGc=.jpg)

此时，赵云杀关羽时距离$D = 1$。而关羽想杀赵云时距离$D = 2$。

# Standard Input

第一行为$T$（$1\leq T\leq 10$），表示测试数据组数。

每组数据第一行为两个整数$N$,$M$ 。（$2\leq N\leq 1000$ ，$1\leq M\leq 1000$）

接下来有$M$行,每一行格式为 
* `N1 S Num` （$1\leq N\_1\leq N$ ， $S$ 为 `+` 或 `-` ，$1\leq Num\leq 100$，$N\_1$和$Num$均为整数）
* `K A B` （$1\leq A,B\leq N$，$A\neq B$，$A$、$B$都是整数）

假定游戏中无人阵亡。

# Standard Output

对于为每组数据，先输出一行 `Case #C:`，$C$ 对应数据组数，$C$ 从$1$ 到 $T$ 。

对于每一个格式为 `K A B` 的操作，则输出 `Yes!` 或 `I'm sorry.` 。

**每组数据之后有一个空行。**

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2
3 1
K 1 3
5 4
K 1 3
K 1 2
1 - 1
K 1 4</td><td>Case #1:
Yes!

Case #2:
I'm sorry.
Yes!
Yes!</td></tr></table>


# Constraints



# Note



# Source


