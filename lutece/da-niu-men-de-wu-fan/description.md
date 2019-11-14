
# Content

大家都知道ACM比赛有提供午饭的传统,正好最近学校要举办程序设计竞赛，可是ACM大牛们都去打比赛去了.只剩下弱菜Saerdna一个人负责大牛们的午饭.因为负责送那么多大牛的午饭是一件很累的活，所以Saerdna当然希望每位大牛都吃得少一点，最好都不吃。。。。但是不送午饭又说不过去，所以对于每个大牛，Saerdna都会送去一份午饭。

因为每个大牛都有一个大牛值，所以大牛之间都会暗自较劲，为了不让大牛们起冲突，Saerdna送去的午饭必需保证相邻两个大牛之间存在以下关系,大牛值大的大牛得到的午饭比大牛值小的大牛要多。

# Standard Input

一开始是一个数字$T$($T\leq 10$)表示数据组数

接下来$T$行，每行是一个数$n$.($n\leq 10^6$)

接下来一行有$n$个数，表示每个大牛的大牛值。

# Standard Output

Saerdna最少需要送多少饭

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
3
1 2 3
4
3 1 2 2</td><td>6
6</td></tr></table>


# Constraints



# Note

第一个Sample中 第$1$个大牛送$1$份饭,第$2$个大牛送$2$份饭,第三个大牛送$3$份饭.

第二个Sample中 第$1$个大牛送$2$份饭,第$2$个大牛送$1$份饭,第三个大牛送$2$份饭.最后一个大牛送一份饭,因为最后两个大牛的大牛值不是严格大于.

# Source


