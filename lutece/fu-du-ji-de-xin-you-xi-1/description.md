
# Content

那一天，复读机回忆起了被群管理支配着的恐惧，和被禁言无尽的痛苦。在qh消灭复读机后，迎来了短暂的和平，复读机无法在明面上复读，但是背地里群聊总是暗流涌动，复读机们重新积蓄力量，一场人类本质的复兴运动正在悄然展开。

复读机准备在群里举办复读狂欢夜，为此他们准备了一个小游戏，负责情报的复读机在被禁言前，将两份包含游戏规则的文本 $S$ 和 $T$ 交给了你，然后就被禁言了。文本中含有重要的狂欢夜游戏规则的情报，$S(l,r)$表示字符串$S$从$l$ 到 $r$位置字符构成的字串，$T(l,r)$同理，加号代表字符串拼接。若 $S(l,mid)+T(mid,r)$ 是回文串$(l\le mid \le r )$ ，那么这个回文串就是一份疑似情报，**并且 $S$ 和 $T$ 的回文子串也是一份疑似情报**。现在上级复读机需要你找出长度最长的疑似情报，这样获得的信息最多。

# Standard Input

第一行包含一个字符串 $S(1\le |S| \le 5\times10^5)$ ，含义如上。

第二行包含一个字符串 $T(1\le |T| \le 5\times10^5)$ ，含义如上，输入保证$|S|=|T|$且仅由小写字母(a - z)构成。

# Standard Output

输出包含一个个正整数，最长的疑似情报的长度

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
<tr><td>abc
cba</td><td>4</td></tr><tr><td>abaabaaba
abaabaaba</td><td>10</td></tr></table>


# Constraints



# Note



# Source


