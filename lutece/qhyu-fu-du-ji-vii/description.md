
# Content

最近复读机喜欢复读数字串。

qh发现带头复读的复读机复读的数字串都是回文串。

qh在导出聊天记录的时候忘了将群名片一同导出，但他知道不同的带头复读机复读的数字串都互不相同。

qh想将所有复读机一起禁言，且时长为未被分割的聊天记录中所有`不同`的回文数字串的数值之和。

如$12121$中有$1,2,121,212,12121$这五种不同的回文数字串，他们的和为$1+2+121+212+12121=12457$

因为这个数可能很大，而QQ所支持的最长禁言时间为$T$秒，所以qh决定若上述的数值之和为$t$，那么他最终将把所有复读机一起禁言$t$ $mod$ $T$秒。

qh不想在这种简单的问题上花时间，于是他把问题丢给了你。

# Standard Input

第一行有一个由$0-9$组成的字符串$S$，代表未被分割的聊天记录。

第二行有一个数$T$，代表QQ支持的最长禁言时间。

# Standard Output

输出最终的禁言时长。

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
<tr><td>12121
114514</td><td>12457</td></tr></table>


# Constraints

$1 \leq |S| \leq 10^6$

$1 \leq T \leq 10^9$

# Note



# Source


