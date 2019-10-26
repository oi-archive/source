
# Content

Dan，Eve和Faker正在玩纸牌游戏，如下所示：  
起初，每名玩家都有一些牌组成的牌组。每张卡上都写有一个字母$D$，$E$或$F$。卡组的卡片顺序不能重新排列。  
球员轮流。Dan先走。  
如果当前玩家的牌组至少包含一张牌，则丢弃牌组中的第一张牌。然后，名字以丢弃的卡片上字母开头的玩家进行下一轮。 （例如，如果卡片上写着$D$，Dan会下一个回合。）  
如果当前玩家的牌组是空的，则游戏结束并且当前玩家赢得游戏。  
给定玩家的最初牌组。更具体地说，给定三个字符串$S_D$，$S_E$和$S_F$。 $S_D$中的第$i$个字母是Dan初始牌组中第$i$张牌上的字母。 $S_E$和$S_F$以同样的方式描述了Eve和Faker的初始牌组。  
确定游戏的胜利者。

# Standard Input

标准输入的输入格式如下：  
$S_D$  
$S_E$  
$S_F$  
数据保证:  
$S_D,S_E,S_F$的长度小等于100  
$S_D,S_E,S_F$中只包含$D$，$E$或$F$。

# Standard Output

如果Dan会赢，打印D.  
如果Eve赢了，打印E.  
如果Faker赢了，打印F。

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
<tr><td>DFD
DFFF
FD</td><td>D</td></tr></table>


# Constraints



# Note

游戏进程：D，D，F，F，D。  
**建议使用长度为101位的char数组保存输入(字符串结尾有一个\0)**

# Source


