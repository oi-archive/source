
# Content

qh今天想杀一批复读机。

qh把最近几天的聊天记录扒了出来。

qh截取了一段聊天记录，记代表这段聊天记录的字符串为$S$。

qh知道这群复读机在复读，且第一个复读机的发言被完整截取了，但不知道第一个复读机的发言长度。

如截取的这段聊天记录为abaaaba，则有三种可能：

1. 第一个复读机说了一句abaaaba，后面尝试复读的复读机被禁言了无法复读。

2. 第一个复读机说了一句abaaab，第二个复读机跟着复读abaaab但只有第一个字符被截取了（说到一半就被杀了）。

3. 第一个复读机说了一句abaa，第二个复读机跟着复读abaa但只有前三个字符被截取了（说到一半就被杀了）。

qh想知道所有的可能性，即第一个复读机所有可能的发言长度。

检查所有的可能性非常耗时，于是qh把这件事丢给了后缀复读机。

后缀复读机有一万个ddl要赶，没时间看聊天记录。

你能帮后缀复读机解决检查聊天记录的问题吗？

# Standard Input

第一行有一个仅由空格之外的ASCII可见字符组成的字符串$S$，代表qh截取的聊天记录。

# Standard Output

输出一行，代表所有的可能性。

从小到大依次输出，两个数之间用空格分隔。

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
<tr><td>abaaaba</td><td>4 6 7</td></tr></table>


# Constraints

$1\leq |S| \leq 10^6$

# Note



# Source


