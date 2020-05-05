
# Content

![pic](https://media.st.dl.bscstorage.net/steam/apps/250320/ss_c8c2cf0603f6a956fa4a514a051b0ace5081bed8.600x338.jpg?t=1570653924)

童话镇，一个充满了黑暗、血腥、犯罪的城市。在这里，有着最为庞大的地下组织。组织每天做着地下交易，无恶不作。在这里，每天都会有人离奇失踪，甚至死亡。

我们的警长毕格比·沃夫今天又接到一件案子：费丝小姐被杀害了！经过调查，沃夫隐隐感觉这起案件一定与那个组织有关。于是，他在现场找来了 $n$ 个证人。

沃夫是一名无比老练的警长，他只对每个人询问两种问题：

1. 你是不是组织中的人？
2. 那个人（沃夫指定一个人）是不是组织中的人？

每一个问题，被询问者只能回答“是”或“否”。组织的人很狡猾，他们只会说假话；而善良的普通市民只会说真话。这 $n$ 个人都互相知道对方的身份。沃夫并不知道这些人里面有多少个组织中的人，只知道这 $n$ 个人中普通市民的人数一定**不少于**组织中的人。现在，沃夫想知道：对于**所有**情况，沃夫是否都能将每个人的身份辨别出来？

# Standard Input

输入仅一个整数 $n$ ($1 \leq n \leq 10^9$)。

# Standard Output

如果沃夫能够在所有情况下将每个人的身份辨别出来，则输出 `YES`，反之，则输出 `NO`。（区分大小写）

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
<tr><td>3</td><td>YES</td></tr><tr><td>2</td><td>NO</td></tr></table>


# Constraints



# Note

对“**所有**情况”的解释：

$n=3$ 时，设 $3$ 人分别为 $1$ 号、$2$ 号、$3$ 号，所有情况如下：

1. $1$ 号为好人，$2$ 号为好人，$3$ 号为好人。
2. $1$ 号为好人，$2$ 号为好人，$3$ 号为坏人。
3. $1$ 号为好人，$2$ 号为坏人，$3$ 号为好人。
4. $1$ 号为坏人，$2$ 号为好人，$3$ 号为好人。

# Source


