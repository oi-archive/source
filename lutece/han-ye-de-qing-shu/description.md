
# Content

某年某月某日，韩爷被妹子表白了\o/

同时，韩爷收到了来自妹子的情书。在好奇心的驱使下，众人想要一览究竟。
显然，羞涩韩爷是不会把情书直接拿出来的。
假设情书长度为$n+2$，韩爷从中提取出$n$个长度为3的连续字符串，分给了$n$个人。

现在这n个人向你求助，能否帮他们把情书恢复出来。

# Standard Input

第一行一个数字 $n\ (1 \leq n \leq 2\cdot 10^5) $表示有$n$个字符串

接下来$n$行，每行是三个字符组成的字符串。字符可能是小写字母、大写字母或数字。

注意可能会有相同的字符串。

# Standard Output

如果韩爷耍了小聪明的，即所求的字符串并不存在，输出`NO`

否则，输出`YES`，并且输出任意一个可能的字符串。

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
<tr><td>4
baa
caa
aax
aay</td><td>NO</td></tr><tr><td>5
123
234
345
456
567</td><td>YES
1234567</td></tr><tr><td>3
123
231
312</td><td>YES
23123</td></tr></table>


# Constraints



# Note

当字符串存在时，字符串可能不唯一，比如样例3下，12312、31231也是符合题意的。

# Source


