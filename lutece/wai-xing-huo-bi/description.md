
# Content

![pic](https://media.st.dl.bscstorage.net/steam/apps/275850/ss_4943fff4921ad1b679ce4ad0e6b8664073bd37e6.600x338.jpg?t=1569942160)

在距离地球 $114514$ 光年外的星系，有一颗 cdy 星球，那里也有着高度的文明。cdy 星球上的居民也是用货币交换商品，但与地球的体系有所不同。cdy 星上的货币都是正整数面额的，并且一件价格为 $x$ 的商品必须用面额**恰好**为 $x$ 的货币交换。与地球更不同的是，cdy 星上的货币可以进行合成：一个面值为 $a$ 和一个面值为 $b$ 的货币，可以合成一个面值为 $a+b$ 或者面值为 $|a-b|$ 的货币（合成 $|a-b|$ 的货币时必须满足 $a \ne b$），合成后原来的两个货币消失，新的货币可以与其他货币继续合成。

cjh 是 cdy 星球上的一个居民。这天，cjh 想出门买东西，但他忘记那个东西的价格了，只记得那个东西的价格是不超过 $n$ 的正整数。他家里有任意正整数面额的货币，但每种面额的货币有且只有一个。他想带尽可能少的货币，使得不管那个东西的价格是多少，他都能给出对应面额的货币。他想知道，他最少需要带多少货币。

# Standard Input

第一行包含一个正整数 $n$，$1 \le n \le 10^{18}$。

# Standard Output

输出一个整数，表示最少需要的货币个数。

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
<tr><td>20</td><td>4</td></tr></table>


# Constraints



# Note

样例解释：可以选择带面额为 $1,2,6,11$ 的货币（方法不唯一）。如果价格为 $16$，可以用 $1$ 和 $6$ 合成 $|6-1|=5$，再用 $5$ 和 $11$ 合成 $5+11=16$。其他价格也都有相应方案。

# Source


