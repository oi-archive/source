
# Content

Lutece计划上线一个新功能，比赛封榜前实时广播队伍的提交与过题情况。$Pxt$已经完成了一个智能屏幕监测程序，每当一支队伍通过一道新题目后，更新一个事件记录该队在此题上的罚时。$Pxt$想知道他所在的1号队伍的实时排名，这样他就不用反复在题目与排行榜间切换。

对于任意两支队伍$t_1,t_2$，$t_1$排名比$t_2$高当且仅当$t_1$通过题数比$t_2$多，或$t_1$和$t_2$通过题数相等时$t_1$罚时更小。一支队伍的排名为排名比它高的队伍数量加一。

$Pxt$现在想睡午觉，于是他就把这个简单的任务交给你了。

# Standard Input

第1行两个正整数$n,m$，表示有$n$支队伍，$Pxt$的屏幕监测程序记录了$m$个事件。

第2至$m+1$行，每行两个整数$t,p$，表示$t$号队伍通过了一道新题目，他们的罚时为$p$。

# Standard Output

$m$行，第$i$行一个整数表示第$i$个事件后1号队伍的排名。

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
<tr><td>3 4
2 7
3 5
1 6
1 9</td><td>2
3
2
1</td></tr></table>


# Constraints

$1≤n,m≤100,000$

$1≤t≤n$

$1≤p≤1000$

# Note



# Source


