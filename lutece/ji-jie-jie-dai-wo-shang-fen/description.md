
# Content

- MahjongForces开启段位赛模式啦！大家都希望洁姐姐能带我们上分!MahjongForces的比赛规则规定每场比赛最多能有k个相同段位的人组队参加，每场比赛后会根据比赛结果提升或降低段位。（为了使题目变得更简单，我们假设MahjongForces只有一高一低两个段位，并且最初所有人都在低段位）

- 虽然洁姐姐非常的优秀，以至于洁姐姐能随意的操纵比赛结果来达到自己想要的效果（提升或者降低段位），但是队伍中有多少成员就会消耗洁姐姐多少体力，洁姐姐并不想花费太多的体力在MahjongForces上面。注意，尽管如此，洁姐姐仍然需要参加每一场比赛。 
- 同时，成员中存在许多CP关系，这些CP在处于相同段位，并且洁姐姐不在该段位时，他们就会悄悄的跑去双排，由于洁姐姐目前仍然单身，洁姐姐非常不希望发生这种情况。
- 你们帮洁姐姐计算带所有人上分需要花费多少体力吗？

# Standard Input

- 第一行包含三个整数n，m，k,表示除洁姐姐外共有n个人，其中有m对CP关系，比赛规则规定每次最多k个人参加(1 <= n, m <= 15, 1 <= k <= n)
- 接下来的m行每行两个整数ai和bi，表示当ai与bi之间存在CP关系（即不能出现ai与bi位于同一段位且洁姐姐不在该段位的情况）

# Standard Output

若洁姐姐能带所有人达到高段位，即输出最小需要花费的体力，否则输出“mole”（不包括引号）

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
<tr><td>3 2 2
1 2
1 3</td><td>12</td></tr><tr><td>3 2 1
1 2
1 3</td><td>mole</td></tr></table>


# Constraints



# Note

- 样例1中，洁姐姐首先带编号为1的人到高段位（消耗为2），再自己返回低段位（消耗为1），再带编号为2的人到高段位（消耗为2），再带编号为1的人返回低段位（消耗为2，高段位仅有2），再带编号为3的人到高段位（消耗为2），再自己返回低段位（消耗为1），最后带编号为1的人到高段位（消耗为2）
- 总消耗为2+1+2+2+2+1+2=12

# Source


