
# Content

“学习本无底，前进莫徬徨。” 秋实大哥对一旁玩手机的学弟说道。

秋实大哥是一个爱学习的人，今天他刚刚学习了线段树这个数据结构。

为了检验自己的掌握程度，秋实大哥给自己出了一个题，同时邀请大家一起来作。

秋实大哥的题目要求你维护一个序列，支持两种操作：一种是修改某一个元素的值；一种是询问一段区间的和。

# Standard Input

第一行包含一个整数$n$，表示序列的长度。

接下来一行包含$n$个整数$a\_i$，表示序列初始的元素。

接下来一行包含一个整数$m$，表示操作数。

接下来$m$行，每行是以下两种操作之一：
- 1 x v : 表示将第x个元素的值改为v  
- 2 l r : 表示询问[l,r]这个区间的元素和

$1\leq n，m，v，a\_i\leq 100000$，$1\leq l\leq r\leq n$。

# Standard Output

对于每一个$2$ $l$ $r$操作，输出一个整数占一行，表示对应的答案。

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
<tr><td>3
1 2 3
3
2 1 2
1 1 5
2 1 2</td><td>3
7</td></tr></table>


# Constraints



# Note



# Source


