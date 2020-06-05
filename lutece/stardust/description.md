
# Content

总之就是想要打牌。

“聚集的祈愿将成为新生的闪耀之星，化作光芒闪耀的.......”诶，星星不见了？出于种种原因，同调召唤所需要的星星受到了干扰，各处使用同调召唤的决斗者所期望的星星状态无法被满足。

现在天空中有 $n$ 颗星星，标号 $1$ 到 $n$。每颗星星都有闪耀和暗淡两种状态。每位决斗者希望其中特定的 $3$ 颗星星至少有两颗处于他们期望的状态。例如，某位决斗者希望第三颗星星闪耀、第五颗星星暗淡、第七颗星星暗淡，则对于第三、第五、第七颗星星来说，{闪耀、暗淡、暗淡}、{暗淡、暗淡、暗淡}、{闪耀、闪耀、暗淡}、{闪耀、暗淡、闪耀} 均满足要求。

OrangeRain 想让这个世界充满笑容，为此他想要通过任意改变星星状态来满足每一位决斗者的要求，但他不知道是否能做到，你能帮帮他吗？

# Standard Input

第一行包含两个正整数 $n,m$ ($3 \leq n \leq 100000$，$1 \leq m \leq 100000$)，代表有 $n$ 颗星星，$m$ 位决斗者。

接下来共有 $m$ 行，第 $i$ 行包含六个整数 $a,u,b,v,c,w$（$1 \leq a,b,c \leq n$, $a \neq b$ 且 $a \neq c$ 且 $b \neq c$, $0 \leq u,v,w \leq 1$），表示第 $i$ 位决斗者期望第 $a$ 颗星星处于状态 $u$，第 $b$ 颗星星处于状态 $v$，第 $c$ 颗星星处于状态 $w$，其中状态 $0$ 表示星星暗淡，状态 $1$ 表示星星闪耀。

# Standard Output

若 OrangeRain 能够满足每一位决斗者的要求，则输出 `YES`，否则输出 `NO`。

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
<tr><td>7 5
3 1 5 1 6 0
1 0 2 0 3 1
4 1 5 0 6 0
5 1 6 0 7 0
1 1 2 1 4 1</td><td>YES</td></tr><tr><td>5 6
1 0 3 1 4 0
2 0 3 1 4 1
1 0 2 1 3 1
3 1 4 0 5 0
3 0 4 0 5 0
1 1 2 1 4 1</td><td>NO</td></tr></table>


# Constraints



# Note

样例一中，一种可以满足所有决斗者要求的星星状态为 $\{0,1,1,1,0,0,0\}$

PS：废二是不能带来笑容的啊！

# Source


