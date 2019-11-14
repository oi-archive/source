
# Content

Given $X$`CNY (Chinese yuan)`, can you exchange it to exactly $Y$`CNY` soon? The only way you have is to spend money at a vending machine <u>once</u>, which has an infinite number of copies of merchandise of all possible positive price.

However, you cannot make any assumptions about the way the vending machine will make change; it is only guaranteed that it will dispense banknotes/coins that sum to the amount of change required.

What’s the smallest total amount you have to spend in <u>all</u> case, to get a banknote/coin of $Y$`CNY`?

Only $1$`fen` ($0.01$`CNY`), $2$`fen`, $5$`fen`, $1$`jiao` ($0.1$`CNY`), $2$`jiao`, $5$`jiao`, $1$`yuan` ($1$`CNY`), $2$`yuan`, $5$`yuan`, $10$`yuan`, $20$`yuan`, $50$`yuan` and $100$`yuan` the vending machine will accept or return.

# Standard Input

The first line contains an integer $T$, denoting the number of the test cases.

$T \le 100 $;

Each test case contains two number $X$ and $Y$.

$X,Y \in \\{ 0.01,0.02,0.05,0.1,0.2,0.5,1,2,5,10,20,50,100 \\} $ and $X \gt Y$.

# Standard Output

For each test case, output a number denoting the answer.

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
<tr><td>2
0.05 0.01
0.1 0.01</td><td>0.02
0.07</td></tr></table>


# Constraints



# Note

只要找给你的钱能凑出Y就行

小数点后不要输出多余的位数，比如0.2不要输出0.20

对于任意X，假如你的答案是Z
那么对于X-Z的任意一种组合，都要能凑出Y

The sample input:
If you spend 0.01,you may get 0.02 and 0.02,and can't get 0.01 anymore.

The answer is 0.02,in this case, you can get 0.01,0.01,0,01 or 0.01 0.02.

You can get 0.01 anyway.

# Source


