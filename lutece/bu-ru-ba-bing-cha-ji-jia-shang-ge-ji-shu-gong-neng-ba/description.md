
# Content

在另一个宇宙，一个月有 $N$ 天。多变的天气条件使得人们很恼火，终于，天气统计局产生了。它会对外发布 $M$ 条信息，格式如下：
$X\ Y$ 表示第 $X$ 天的天气和第 $Y$ 天一样。

但民众并不满足于此，他们想知道有多少天的天气和第 $X$ 天一样。
现在，作为一个聪明的程序员，你能帮他们解决这个问题吗？

# Standard Input

第一行包含两个整数$N$和$M$，$N$是总天数，$M$是信息总个数。
接下来的$M$行，每行一条信息。格式为$x\ y$。
然后接下来的一行是一个整数$Q$，表示询问总个数
接下来的$Q$行，每行包含一个数字$z$，表示询问有多少天的天气和第$z$天一样。
$1\le N \le 100000$  $1 \le x, y, z\le N$

# Standard Output

对于每一个询问，输出一行，包含一个整数，表示和$z$天气一样的天数。

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
<tr><td>10 5
1 2
2 3
3 4
1 5
6 7
2
1
6</td><td>5
2</td></tr></table>


# Constraints



# Note



# Source


