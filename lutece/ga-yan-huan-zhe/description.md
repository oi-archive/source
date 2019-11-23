
# Content

![](/source/lutece/ga-yan-huan-zhe/img/aHR0cDovL3d4Mi5zaW5haW1nLmNuL2xhcmdlLzAwNmtudXdQZ3kxZnJkY3kwenowY2czMDk1MDduZTgxLmdpZj9pZD0wP2lkPTA=.gif)

$Huyyt$是$UESTC$知名的嘎癌患者,据悉其患病时间已长达$6$年.神奇的是,只要两个嘎癌患者相识则必互为情敌.

已知新人群中共有$N$名嘎癌患者,他们的标号从$1$到$N$,一开始他们不一定认识其他所有人,于是$Huyyt$决定借用$gakkiの$魔法,每对一个患者使用一次魔法,可以使该患者认识的人之间全部两两相识.

$Huyyt$想知道最少用几次魔法能让$N$名患者中任意两个都是情敌?

# Standard Input

第一行两个数字 $N$ $M$ 表示一开始有 $N$ 个患者 ($1 \le N \le 22$) 和 $M$  ( $0 \le M \le N*(N-1)/2$ ) 对关系.

接下来 $M$ 行.
每行有两个不同的数 $Ai$ $Bi$ ( $1 \le Ai,Bi \le N$ ) 表示标号为 $Ai$ 的人与标号为 $Bi$ 的人初始相识.

# Standard Output

输出满足条件所需要的最少魔法次数

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
<tr><td>5 6
4 5
1 2
1 3
2 3
2 5
3 4</td><td>2</td></tr></table>


# Constraints



# Note

可以先选$2$则$1,2,3,5$四个人任意两个相识,再选$3$则$1,2,3,4,5$全部两两相识.

# Source


