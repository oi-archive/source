
# Content

在整数大陆上，A国向B国发动了战争。

B国的指挥官开始从全国各地募集兵员保卫国家。

为了保证军队战无不胜，指挥官需要测试军队在不同情况下的战斗力并根据情况调整。

军队中的每一个士兵都用他的战斗力$u$来表示。

设由军队中所有士兵的战斗力$u$组成的集合为$S$，则部队在情况$v$下表现出的战斗力会落在一个区间$[min_{u \in S}\{u \oplus v\}, max_{u\in S} \{u \oplus v\}]$内。这里的$v$也是一个正整数，$\oplus$表示[按位异或](https://baike.baidu.com/item/%E4%BD%8D%E8%BF%90%E7%AE%97/6888804?fr=aladdin)。

在征兵过程中，总共发生了$N$个事件，作为指挥官的你需要对这些事件做出适当的反应。

# Standard Input

第一行一个整数$N$，代表总共发生了$N$个事件。

接下来$N$行，每行有两个数$o$和$v$。

当$o=1$时，一个战斗力为$v$士兵加入了军队。

当$o=2$时，一个战斗力为$v$的士兵离开了军队。

当$o=3$时，你发起了一场情况$v$的演习，这时候你需要预估出部队的战斗力。

# Standard Output

对于每一个$o=3$的事件，你需要输出两个数，代表部队战斗力的最小值和最大值，即$min_{u \in S}\{u \oplus v\}和max_{u\in S} \{u \oplus v\}$。

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
<tr><td>5
1 2
1 3
3 5
2 2
3 5</td><td>6 7
6 6
</td></tr></table>


# Constraints

$1 \leq N \leq 5 \times 10^5$

$1 \leq v \leq 2^{30}-1$

对于每个$o=2$的事件，保证当时部队中存在至少一个战斗力为$v$的士兵。

对于每个$o=3$的事件，保证当时部队中至少有一个士兵。

# Note



# Source


