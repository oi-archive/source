
# Content

阿里巴巴和$n$个大盗来到了一个藏满宝石的洞穴。洞里一共有$m$颗价值连城的宝石，每一颗都等价。盗亦有道，为了奖励帮忙打开洞穴门的阿里巴巴，大盗们决定让他一起加入分赃。大盗们决定采用一种方式分赃，分赃的方式如下：

1）每个人由抽签决定了自己的号码（$1$, $2$, $3$, $\cdots$, $n+1$）。

2）由$n+1$号提出分配方案，然后大家表决，当且仅当超过半数的人同意时（包括他自己），按照他的方案进行分配，否则这个人将被杀死。

3）$n+1$号死后，由$n$号接替$n+1$号对剩下的人提出分配方案，类似$2$步骤。以此类推。

大盗们都有如下的几个性格特点

1）足智多谋，总是采取最优策略。

2）贪生怕死，尽量保全自己性命。

3）贪得无厌，希望自己得到越多宝石越好

4）心狠手辣，在自己利益最大的情况想希望越多人死越好。

5）疑心多虑，不信任彼此，尽量确保自身利益不寄希望与别人给自己更大利益。

不知道是不幸还是幸运，阿里巴巴抽到了$n+1$号签，意味着他将第一个提出分配方案。他想请教机智的你，他能否活下来，如果能又将获得最多多少个宝石？

# Standard Input

两个整数$n$, $m$,分别表示$n$个大盗和$m$个宝石（$1 \leq n \leq 2 \cdot m-2$, $2 \leq m \leq 100$)。

# Standard Output

如果阿里巴巴能活下来输出一个整数$x$表示阿里巴巴最多获得的宝石数，否则输出$-1$。

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
<tr><td>4 100</td><td>97</td></tr></table>


# Constraints



# Note

分配方案 0 2 1 0 97 或2 0 1 0 97（从$1$号到$5$号）。

# Source

