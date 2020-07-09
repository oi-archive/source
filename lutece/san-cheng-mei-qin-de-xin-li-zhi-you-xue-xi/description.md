
# Content

![6343e8b7c2e245ad86bde6e6cf3b987c.jpeg](/source/lutece/san-cheng-mei-qin-de-xin-li-zhi-you-xue-xi/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMjAvbzlBaW1DUVlCMm55SXU3LmpwZw==.jpg)

三澄美琴是一个热爱学习的法医，今天晚上她准备下载很多很多法医论文资料。下面有三个操作

$1\ t_i\ a_i\ b_i$ $i$ 在$t_i$时刻加入了编号为 $a_i$ 耗时为 $b_i$ 的论文进入下载队列

$2\ t_i$ 在 $t_i$时刻取消队列首位的任务(如果下载队列为空就忽略该操作)

$3\ t_i$ 查询在$t_i$时刻队列首位的任务编号，无下载任务输出 `-1`

# Standard Input

第一行一个$n$ $(1\le n\le 10^5)$  
接下来$n$行，每行$j(1\le j\le 3),t_i(1\le t_i\le 10^9)$，当 $j = 1$ 时，$t_i$ 后会跟 $a_i(1\le a_i \le n)$, $b_i(1\le b_i\le 10^4)$

保证 $t_i$ 为升序。

# Standard Output

对于每个3号操作输出一行，输出目前队列首位的论文编号

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
<tr><td>6
1 1 1 5
3 2
1 3 2 3
2 4
3 5
3 6</td><td>1
2
-1</td></tr></table>


# Constraints



# Note

样例解释

操作一：在第1秒加入了编号为1的论文，耗时5秒，将于第6秒完成

操作二：在第1秒查询，队列首位为编号1

操作三：在第3秒加入编号为2的论文下载，耗时3秒，将于第6秒完成，队列里有两个下载任务，队列首位为编号1

操作四：在第4秒移除了编号为1的论文，目前队列里有一个下载任务，队列首位为编号2

操作五：在第5秒查询，队列首位为编号2

操作六：在第6秒查询，此时2号任务刚好完成，队列为空，输出-1

# Source


