
# Content

大家都知道吴神是十分强大的。所以，现在吴神要单挑$n$个敌人。

吴神有两个属性，$hp$和$sp$。$hp$是吴神的健康程度，初始值是$lh$,同时上限也是$lh$。如果$hp\leq 0$那么吴神将输了这场战役。$sp$是吴神用来放技能的值。初始值为$0$，最大值为$ls$。

吴神和他的敌人轮流进行运操作，吴神比较强大，所以先进行操作，然后他的敌人后进行操作。

吴神每回合可以有如下的操作：
1. 杀死一个敌人并且使自己的$sp+1$.
2. 治愈他自己使$hp$增加$lh/5$的值。（注意$/$表示下取整）
3. 或者，他可以用技能如果$sp>0$时，那么会杀死$d[sp]$的人，$sp=0$，$d$是给定的数组。
4. 什么也不干。

他的敌人会在吴神操作玩后，进行攻击，他们每个人对吴神造成$1$点伤害，也就是使$hp-1$。

最后，吴神的$sp$的值会增加 剩余敌人数模$3$的值。

现在，吴神想知道最少多少个回合，能够团灭敌人，取得战役的胜利。

# Standard Input

多组测试数据。一直读到文件末尾。

每组测试数据两行，第一行$3$个数字，以空格隔开。他们是分别代表$lh$($1\leq lh\leq 250$), $ls$($1\leq ls\leq 100$), $n$（$1\leq n\leq 40$）。

第二行是$ls$个数字以空格隔开，第$i$个数字表示$d[i]$。

# Standard Output

$1$个样例占$1$行，如果能赢战役，输出最少需要的回合数字，如果不能赢，输出`HELP!`。

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
<tr><td>5 2 4
2 3</td><td>3</td></tr></table>


# Constraints



# Note



# Source


