
# Content

大学生足球联赛火热来袭，共有$N$（$N$为偶数）支大学球队报名参加了这次比赛。联赛采取单循环制，每只球队需要跟其他$N-1$支球队交手一次。赛事共有$N-1$轮，每轮有$\frac{N}{2}$场比赛，每一轮每支球队都得出场比赛。你是本届赛事的负责人，队伍的编号为$1$~$N$，请你安排一个$N$支球队$N-1$轮的赛程表。

# Standard Input

一个整数$N$，代表报名参赛的大学球队数。$(2 \leq N \leq 66)$

# Standard Output

输出共有$N-1$行，第$i$行代表第$i$轮的对阵情况。

对于每一行，共有$N$个数，用空格相隔，其中第$2 \times j-1$个数和第$2 \times j$个数代表该轮第$j$组比赛对阵。

赛程表有很多种可能，你只需输出任意一组合法的赛程表即可。

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
<tr><td>2</td><td>1 2</td></tr><tr><td>4</td><td>1 2 3 4
1 3 2 4
1 4 2 3</td></tr><tr><td>6</td><td>1 2 3 4 5 6
1 3 2 5 4 6
1 4 2 6 3 5
1 5 2 4 3 6
1 6 2 3 4 5</td></tr></table>


# Constraints



# Note

样例$1$，$2$支球队$1$轮赛程表为：

第$1$轮：$1-2$

样例$2$，$4$支球队$3$轮赛程表为：

第$1$轮：$1-2\ 3-4$

第$2$轮：$1-3\ 2-4$

第$3$轮：$1-4\ 2-3$

样例$3$，$6$支球队$5$轮赛程表为：

第$1$轮：$1-2\ 3-4\ 5-6$

第$2$轮：$1-3\ 2-5\ 4-6$

第$3$轮：$1-4\ 2-6\ 3-5$

第$4$轮：$1-5\ 2-4\ 3-6$

第$5$轮：$1-6\ 2-3\ 4-5$

# Source


