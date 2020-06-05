
# Content

宁王是我好兄弟，跟我一起征战 TGA。

宁王和绿毛现在面临一个问题，一个陌生人给了他们 $n$ 个物品。第一个物品给了宁王，最后一个给了绿毛，其余的要求他们自己分配。宁王拿到物品 $i$ 则获得 $a_i$ 点价值，绿毛拿到则获得 $b_i$ 点价值。并且某些物品在一起会有附加价值，有 $m$ 对这样的物品，当他们同时在宁王手中，则额外获得 $c$ 点价值；同时在绿毛手中，则额外获得 $d$ 点价值；但是一个在宁王手中，一个在绿毛手中，则会倒扣 $e$ 点价值。

宁王和绿毛想要获得最大的价值，但是他们不知道怎么获得，于是他们找到了你。

# Standard Input

第一行包含两个正整数 $n,m$ ($3 \leq n \leq 10^4,1\leq m \leq 10^4$)，表示物品个数和有附加价值的物品对数。

第二行包含 $n-2$ 个正整数 $a_2,a_3,\dots,a_{n-1}$ ($1 \leq a_i \leq 10^4$)，规定 $a_1=0$。

第三行包含 $n-2$ 个正整数 $b_2,b_3,\dots,b_{n-1}$ ($1 \leq b_i \leq 10^4$)，规定 $b_n=0$。

接下来 $m$ 行，每行包括五个正整数 $u,v,c,d,e$ ($1\leq u,v \leq n,u \neq v,1 \le c,d,e \le 10^4$)，表示物品 $u,v$ 有附加价值，含义见题目描述。数据保证无重复的物品对。

# Standard Output

输出一个整数，表示能获得的最大价值。

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
<tr><td>3 1
1
1
1 3 10 1000 1</td><td>0</td></tr></table>


# Constraints



# Note

对于样例，物品 $1$ 和 $3$ 必然在不同的人手中，所以倒扣 $1$ 点价值，而物品 $2$ 分给谁都是 $1$ 点价值，所以最大价值是 $0$。

# Source


