
# Content

过年了！cxx家迎来了非常多的亲戚朋友，cxx数了一数总共有$n$个。她们一起坐在巨大的客厅看巨大的电视，每个亲戚都有一些喜欢的电视频道，如果他成功看到了**所有**他喜欢的电视频道，他就会非常开心，并且给cxx一些压岁钱。但是cxx家现在还没有开通任何一个电视频道，因为平常不看电视。现在cxx正在打电话给电视公司购买要看的电视频道（我们假设如果cxx购买了一个电视频道，亲戚们就一定会看到这个电视频道），cxx可以任意选择购买哪些电视频道，或者不买。每个电视频道有一定的价格，cxx想知道她除去购买频道的钱，最多能剩下多少压岁钱呢？

# Standard Input

第一行两个正整数$n(\leq 10000),m(\leq 10000)$表示亲戚数量，电视频道的数量。

第二行$m$个数表示购买每个电视频道的价格。($\leq 10^5$)

接下来$n$行每行表示了一个亲戚的信息，首先有一个正整数$c(\leq 10^5)$表示如果他看到了所有他喜欢的频道，会给cxx多少压岁钱，然后一个正整数 
$k$表示该亲戚有$k$个喜欢的电视频道，紧接着有$k$个数表示具体是哪k个电视频道。$(\sum k\leq 200000 )$

# Standard Output

一行一个整数表示cxx最多能剩下多少压岁钱

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
<tr><td>4 4 
4 6 3 8
3 2 1 3
5 2 1 3
7 3 1 3 4
6 2 2 4</td><td>1</td></tr></table>


# Constraints



# Note

购买频道1,3。

# Source


