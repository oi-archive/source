
# Content

众所周知，$FIFA\ Online3$是一款风靡全球的足球游戏。

![title](/source/lutece/fifa-online3/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyOS8yMDE3MTEyMTIwNTcxODgwNTEyLmpwZw==.jpg)

在这里，你是球队的教练，需要通过购买、交换或者开球员包来获取球员，组建你的球队。

我们知道，足球是$11$个人的运动，一只出色的球队，离不开团队协作。

同时，个人能力出众的球员也更受大家的青睐。

![title](/source/lutece/fifa-online3/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyOS8yMDE3MTEyMTIyMDIzMjc4ODEzLmpwZw==.jpg)

越优秀的球员，其基本能力值越高。但一名球员的综合能力值，还有以下$5$种加成属性：

$1$.经验加成

一名球员初始等级为$Lv.1$，每升$1$级，能力值$+1$.如一名球员的等级为$Lv.11$，其经验加成可以使能力值$+10$.

$2$.个人强化等级加成

一名球员的基本能力值为$0$卡，你可以对这名球员进行强化来提升他的能力值，强化等级及能力加成对应表如下：

![title](/source/lutece/fifa-online3/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyOS8yMDE3MTEyMTIyMjY0NjczNjE0LnBuZw==.png)

$3$.球队强化等级加成

强化等级为$0$、$+1$的球员卡为铁卡，强化等级为$+2$、$+3$、$+4$的球员卡为铜卡，强化等级为$+5$、$+6$、$+7$的球员卡为银卡，强化等级为$+8$、$+9$、$+10$的球员卡为金卡。

如果有$6$名及以上队员强化等级在$+2$及以上，这些队员能力值$+1$.

如果有$6$名及以上队员强化等级在$+3$及以上，这些队员能力值$+2$.

如果有$6$名及以上队员强化等级在$+5$及以上，这些队员能力值$+3$.

如果有$6$名及以上队员强化等级在$+8$及以上，这些队员能力值$+4$.

当然，如果一名队员满足以上多种加成条件，则取其最高值进行加成。

$4$.队套加成

队套加成分为俱乐部加成和国家队加成。

如果一支球队里有$6$~$8$名球员来自同一俱乐部，则这些球员能力值$+2$；如果有$9$~$11$名球员来自同一俱乐部，则这些球员能力值$+3$.

同理，如果一支球员里有$6$~$8$名队员来自同一国家，则这些球员能力值$+2$；如果有$9$~$11$名球员来自同一国家，则这些球员能力值$+3$.

俱乐部加成和国家队加成不能叠加。如果一名队员既有俱乐部加成又有国家队加成，则取两者较高值为该名球员的队套加成。

注意：$0$卡的球员不能进行队套加成。

$5$.助理教练加成

助理教练分为门将教练、后卫教练、中场教练和前锋教练。一名教练只能对自己所指导位置的球员有加成作用。教练的星级为$1$~$5$级，$q$星级的教练能使该位置的所有球员能力值$+q$，若$q=0$则说明缺少该位置的助理教练。

现实游戏中还会有其他的加成，例如周最佳球员；助理教练里还有医疗教练和全能教练，我们这里不予考虑。

球队阵型：一支球队的阵型通常以“$x-y-z$”的形式进行表示，表示有$x$名后卫队员，$y$名中场队员和$z$名前锋队员。阵型不包括门将，所以$x+y+z=10$.常见的阵型有“$4-3-3$”、“$4-4-2$”、“$3-5-2$”、“$5-3-2$”等。球员名单会按照门将-后卫-中场-前锋的顺序给出。也就是说在$11$人大名单里，第$1$名队员是门将，第$2$至$2+x-1$名队员是后卫，第$2+x$至$2+x+y-1$名队员是中场，第$2+x+y$至第$11$名队员是前锋。

![title](/source/lutece/fifa-online3/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyOS8yMDE3MTEyMTIyNDExMDU1NDE1LmpwZw==.jpg)

现给你一支球队首发$11$名队员的姓名、基本能力值以及经验等级、强化等级、所属俱乐部、所属国家队等信息，请你计算出每名球员的综合能力值。

# Standard Input

输入共有$13$行。

第$1$行为球队使用的阵型，以$x-y-z$的形式给出，$0<=x,y,z<=10且x+y+z=10$.

第$2$行至第$12$行分别为首发$11$人的信息，由以下六部分构成：

球员姓名 $0$卡能力值 经验等级 强化等级 所属俱乐部 所属国家队

其中，球员姓名、所属俱乐部和所属国家队均为长度不超过$20$的字符串。

$0$卡能力值$P$满足$40<=P<=90$.

经验等级以“$Lv.x$”的形式表示，$1<=x<=20$.

强化等级$0$卡为“$0$”，其余卡以"$+y$"的形式表示，$1<=y<=10$.

第$13$行为$4$个整数$a,b,c,d$，分别代表门将教练、后卫教练、中场教练、前锋教练的星级，$0<=a,b,c,d<=5$.

# Standard Output

输出共有$11$行。

第$i$行代表第$i$名球员的姓名和球员的综合能力值，以空格分隔，按照输入的顺序进行输出。

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
<tr><td>4-3-3
Weidenfeller 72 Lv.16 +7 Borussia-Dortmund Germany
Piszczek 78 Lv.2 +5 Borussia-Dortmund Poland
Hummels 83 Lv.13 +4 Bayern-Munchen Germany
S.Papastathopoulos 81 Lv.15 +10 Borussia-Dortmund Greece
Schmelzer 75 Lv.5 +8 Borussia-Dortmund Germany
Kehl 79 Lv.10 +6 Borussia-Dortmund Germany
Gotze 76 Lv.17 0 Borussia-Dortmund Germany
Kagawa 78 Lv.2 +9 Borussia-Dortmund Japan
Mkhitaryan 80 Lv.18 +1 Manchester-United Armenia
Aubameyang 83 Lv.20 +2 Borussia-Dortmund Gabon
Marco.Reus 81 Lv.9 +3 Borussia-Dortmund Germany
1 2 3 5</td><td>Weidenfeller 108
Piszczek 97
Hummels 109
S.Papastathopoulos 127 
Schmelzer 104
Kehl 109
Gotze 95
Kagawa 108 
Mkhitaryan 107 
Aubameyang 117 
Marco.Reus 106 </td></tr></table>


# Constraints



# Note



# Source


