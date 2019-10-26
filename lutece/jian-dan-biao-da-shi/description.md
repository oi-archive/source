
# Content

LZH和TJL每天在一起太无聊，就想了一个打发时光的办法。LZH给TJL写了一个算术表达式，让TJL计算结果。这个算术表达式比较简单，只包含整数和加号，减号。但整数不一定都是十进制的数，可能是八进制，十六进制，LZH规定包含前缀`0x`的是十六进制，包含前缀`0`的是八进制，其他情况是十进制。TJL觉得这实在太累了，你能写程序帮帮他吗。

题目保证给定的算术表达式是以下格式：
```
整数+(-)整数+(-)整数……+(-)整数
```

整数只有三种形式：十进制、八进制、十六进制，保证给定的整数不会超过$6$位(包含前缀`0x`或前缀`0`)。

如`027555+692-0xD32C`就是一个标准的算术表达式。

# Standard Input

第一行数据组数$T$($T\leq 100$)。接下来$T$行每一行包含一个标准的算术表达式，只可能包含数字，小写字母`x`，大写字母`A`到`F`，`+`，`-`。字符串的长度不超过$1000$。

# Standard Output

输出T行，每一行输出表达式的结果，注意结果是十进制的。

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
1+2
027555+692-0xD32C</td><td>3
-41227</td></tr></table>


# Constraints



# Note



# Source


