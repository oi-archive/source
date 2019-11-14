
# Content

电子科技太学图书馆创建于1956年，馆舍总面积66974平方米，各类阅览室37个，阅览座位10023个（含在建新馆），馆藏总量371.8万册。

为了更好地管理数量如此庞大的书籍，管理员准备对所有书籍进行一次统计、整理。图书管理员需要将相似的图书归为一类，为此它为每个分类选出了几个关键词，如果在一本书的文本中，关键词出现得越频繁，则说明这本书越有可能属于这一类。

现在，管理员把这项重任交给你，并希望在太阳完全下山之前能够统计出每个关键词在书本中出现次数的总和。

注：重复关键词重复统计。

# Standard Input

输入文件中第一行一个正整数 $T$ 表示测试数据组数。

每组测试数据第一行为书籍内容，为长度不大于 1000000 的字符串 $S$。

第二行为不多于 10000 的整数 $N$ ，表示关键词个数，接下去 $N$ 行，每行有长度不超过 50 的关键词字符串。

数据保证字符串只由英文小写字母 a-z 组成，不存在空串。 $T\times|S|\le10000000$

# Standard Output

每组测试数据输出一行，为每个关键词在书本中出现次数的总和。

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
<tr><td>1
trumpet
5
trump
drum
pet
rump
rua</td><td>3</td></tr></table>


# Constraints



# Note

trumpet 中出现了 trump pet rump 。

# Source


