
# Content

qh今天想杀一批复读机。

qh把最近几天的聊天记录扒了出来，用一种神奇的编码方式将聊天记录转换成了由小写字母组成的字符串。

记代表聊天记录的字符串为$S$。

qh又找到了一个神奇的模板串$T$，如果qh发现对于$T$的某个前缀$T_{1...i}$，存在$S$的一个比$T_{1...i}$长的子串$S_{l...r}$使得$S_{l...r}+T_{1...i}$为回文串（这里的加号为字符串连接），就会将那个复读机禁言1分钟。

检查聊天记录非常耗时，于是qh把这件事丢给了后缀复读机。

后缀复读机有一万个ddl要赶，没时间看聊天记录。

你能帮后缀复读机解决检查聊天记录的问题吗？

# Standard Input

第一行有一个仅由小写字母组成的字符串$S$。

第二行有一个仅由小写字母组成的字符串$T$。

# Standard Output

输出qh的总禁言时长，即每存在一对不同$S$的子串$S_{l...r}$与$T$的前缀$T_{1...i}$，qh便会将某个人禁言一分钟。

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
<tr><td>ababa
aba</td><td>5</td></tr><tr><td>aabbaa
aabb
</td><td>7
</td></tr></table>


# Constraints

$1\leq |S| \leq 10^6$

$1\leq |T| \leq 10^6$

# Note

时限是标程的几十倍，欢迎使用各种方法通过此题。

一个字符串$S$是回文串当且仅当$\forall i \in \{ 1, 2, ..., |S| \}, S_i=S_{|S|-i+1}$，即这个字符串反过来后和原串相等。

第一个样例解释：共有$5$对满足条件：

$(S_{1...4},T_{1...3}),(S_{1...4},T_{1...1}),(S_{2...4},T_{1...2}),(S_{1..2},T_{1...1}),(S_{3...4},T_{1...1})$

它们的值分别是：

$(abab,aba),(abab,a),(bab,ab),(ab,a),(ab,a)$

# Source


