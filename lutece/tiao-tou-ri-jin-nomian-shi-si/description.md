
# Content

省府弟子乐天潭在条头日今的笔试中遇到了四道题，其中第四题是：

条头日今有一个庞大的数据库，这些数据由 n 行 m 列的服务器集群保存着。

为了保护服务器不被入侵，每台服务器都设置了密码。一共有 p 种密码，每台服务器只设置其中一种密码。

而第 i 种密码保存在所有设置为第 i-1 种密码的服务器上。保证每种密码至少设置在一个服务器上，且第p种密码只有一台服务器设置。

现在你在第 1 行第 1 列服务器的位置，题目告诉你了第 1 种密码以及每个服务器设置了哪种密码。

你只能向当前所在服务器的前后左右移动（如果那个位置有服务器的话），每移动一次花费一个单位时间，获取密码时间不计。

现在题目要你写出打开设置了第 p 种密码的服务器所需要的最小时间。

乐天潭很强势，一眼就知道了解法，但计算量实在过大，没办法只好偷偷掏出手机请你帮他写一个程序算出答案。

# Standard Input

第一行，三个整数n (1 <= n <= 300)，m (1 <= m <= 300)，p (1 <= p <= n*m)。

接下来 n 行，每行 m 个整数 aij 表示第 i 行 j 列的服务器所设置的密码类型为 aij。

# Standard Output

输出一行，表示打开设置了第p种密码的服务器所需要的最小时间。

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
<tr><td>3 3 4
1 1 2
1 1 2
3 3 4</td><td>6</td></tr></table>


# Constraints



# Note



# Source


