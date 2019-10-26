
# Content

`eom`在玩galgame！与一般的galgame不同的是，你需要氪金抽卡抽到妹子才能攻略她们。这个游戏的抽卡系统也与一般的游戏有所不同，在一次抽取中有x的概率抽到一个特定的妹子，也有y的概率抽到该妹子的一个**特定**碎片。除了直接抽到某个妹子，凑齐她的m个不同碎片也能解锁该妹子。`eom`有一个无论如何都想抽到的妹子，但他剩下的钱只够他再抽n次了，请你告诉他他能在n次内能抽到的概率p。

# Standard Input

第一行有两个个整数n和m，含义见题目描述。

第二行有两个浮点数x，y，含义见题目描述。

x和y均以三位小数形式给出。

# Standard Output

为避免精度问题，请输出(p*1000^n)%1000000007。

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
<tr><td>2 2
0.100 0.200</td><td>270000</td></tr></table>


# Constraints

n&le;1e9

m&le;100

# Note

保证x+m*y<=1

样例概率为0.27，乘上1000^2后为270000

# Source


