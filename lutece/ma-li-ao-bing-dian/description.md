
# Content

![title](/source/lutece/ma-li-ao-bing-dian/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyOC8yMDE3MTEyMTE5MDcyMjYzNTEwLmpwZw==.jpg)

你需要到马里奥饼店购买$N$个价值为$K$元的面包。

你有一张$9$折卡，只需要支付面包价钱的$90$%即可得到该面包。

但是，马里奥的$9$折算法只精确到元，如果出现了小数，则采取四舍五入的方式进行收费。

比如说你买$3$个$5$元的面包，共计$15$元，打$9$折后应收费$13.5$元，四舍五入收取$14$元。

如果你买$2$个$3$元的面包，共计$6$元，打$9$折后应收费$5.4$元，四舍五入收取$5$元。

你可以分多次去购买你所需要的$N$个面包，使你的总花费最小。

请问这个最小花费是多少？

# Standard Input

一行两个整数$N,K(1<=N,K<=10)$.

# Standard Output

一行，代表使用$9$折卡购买$N$个价值为$K$元的面包的最小花费。

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
<tr><td>1 1</td><td>1</td></tr><tr><td>2 6</td><td>10</td></tr></table>


# Constraints



# Note

样例$1$，你只有$1$种购买方式，买下这个面包，$1$元打$9$折后应收费$0.9$元，四舍五入收取$1$元。

样例$2$，你有$2$种购买方式：’第一种是一次性买两个面包，共计$12$元，打$9$折后应收费$10.8$元，四舍五入收取$11$元。第二种是分两次购买，每一次买$1$个面包，一次$6$元打$9$折后应收费$5.4$元，四舍五入收取$5$元。两次共花费$5*2=10$元。所以最小花费为$10$元。

# Source


