
# Content

小x和小h是好盆友，小h从小体弱多病，而且还非常健忘，于是把自己平时吃的$n$瓶药都给小x等人保管。  

某一天由于雾都的pm2.5爆表，小h的慢性呼吸道疾病又发作了，但当小x掏出药瓶的时候，却发现了异常情况。  

小x现在有n瓶药，每瓶药里面有无限个药片，每片药重量严格等于1克。但是，吹毛求疵的小x发现$n$瓶药中有2瓶药的每一片药片在重量上是不合格的，不合格的药片比正常药片轻0.1g。  

小x现在有一个电子称$($能够显示具体重量$)$，由于时间紧急，小x决定从每瓶药中选择$b_i(1\le b_i)$个药片，称量它们的总和，并且只称一次，从而找出这两瓶不合格药的编号。

现在，请问最小字典序的序列$b($由$b_i$构成$)$是多少？

# Standard Input

一行一个整数$n(2\le n\le 52)$

# Standard Output

一行$n$个数字,两两间用空格隔开，注意结尾没有空格。

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
<tr><td>3</td><td>1 2 3</td></tr></table>


# Constraints



# Note

若 $a_1,a_2 .. a_n$ 比 $b_1,b_2 .. b_n$ 字典序小，则必存在 $j (1\le j \le n)$ 使得 $a_j$ < $b_j$ 且 对于所有$i<j$都有$a_i = b_i$


样例的解释：如果称出来是5.7g，那么就是第1和第2瓶不合格；如果是5.6g，那么就是第1和第3瓶不合格；如果是5.5g，那么就是第2和第3瓶不合格。

# Source


