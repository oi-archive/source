
# Content

给你$n$个仅由小写字母组成的字符串，请你找出一种[字典序](http://baike.baidu.com/link?url=hQh_mlLd0HTterU5YUtG5hFcUFasfGCizmTQ4erRgDK-bjQGzwp2kYzzCc9QiUuaXwnWzTOZ0PtYdYC65j_YA6cuFXC6q8DATSIkbZS9OI8IklqLsvuTTKJrXGdj8c41)，使得这$n$个字符串在这种字典序下是从小到大排列的.

# Standard Input

第一行一个整数$n\left (1 \leq n \leq 1000  \right )$,表示有$n$个字符串.   
接下来$n$行，每行一个字符串，每个字符串的长度不超过$200$，不含空串.

# Standard Output

如果无解，输出$-1$.    
如果有解，输出一个长度为$26$的字符串，其中第$i$个字母表示这种字典序下第$i$小的字母.     
如果有多个解，输出在字典序$"abcdefghijklmnopqrstuvwxyz"$下最小的那一个.

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
<tr><td>10
petr
egor
endagorion
feferivan
ilovetanyaromanova
kostka
dmitriyh
maratsnowbear
bredorjaguarturnik
cgyforever</td><td>aghjlnopefikdmbcqrstuvwxyz</td></tr></table>


# Constraints



# Note



# Source


