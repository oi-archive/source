
# Content

韩父有$N$个儿子，分别是韩一，韩二…韩$N$。由于韩家演技功底深厚，加上他们间的密切配合，演出获得了巨大成功，票房甚至高达$2000$万。舟子是名很有威望的公知，可是他表面上两袖清风实则内心阴暗，看到韩家红红火火，嫉妒心遂起，便发微薄调侃韩二们站成一列时身高参差不齐。由于舟子的影响力，随口一句便会造成韩家的巨大损失，具体亏损是这样计算的，韩一，韩二…韩$N$站成一排，损失即为$C\times$（韩$i$与韩$i+1$的高度差（$1\leq i<N$））之和，搞不好连女儿都赔了.韩父苦苦思索，决定给韩子们内增高（注意韩子们变矮是不科学的只能增高或什么也不做），增高$1$cm是很容易的，可是增高$10$cm花费就很大了，对任意韩$i$，增高$H$cm的花费是$H^2$.请你帮助韩父让韩家损失最小。

# Standard Input

有若干组数据，一直处理到文件结束。

每组数据第一行为两个整数：韩子数量$N$($1\leq N\leq 50000$)和舟子系数$C$($1\leq C\leq 100$)

接下来$N$行分别是韩i的高度($1\leq h\_i\leq 100$)。

# Standard Output

对每组测试数据用一行输出韩家的最小损失。

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
<tr><td>5 2
2
3
5
1
4</td><td>15</td></tr></table>


# Constraints



# Note

输入数据多请使用`scanf`代替`cin`

# Source


