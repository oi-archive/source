
# Content

密码学是研究如何隐密地传递信息的学科。在现代特别指对信息以及其传输的数学性研究，常被认为是数学和计算机科学的分支，和信息论也密切相关。著名的密码学者`Ron Rivest`解释道：“密码学是关于如何在敌人存在的环境中通讯”，自工程学的角度，这相当于密码学与纯数学的异同。密码学是信息安全等相关议题，如认证、访问控制的核心。密码学的首要目的是隐藏信息的涵义，并不是隐藏信息的存在。密码学也促进了计算机科学，特别是在于电脑与网络安全所使用的技术，如访问控制与信息的机密性。密码学已被应用在日常生活：包括自动柜员机的芯片卡、电脑使用者存取密码、电子商务等等。

现在上级给你这样一个任务：

现已知总的密码长度$n$，并且在间谍的帮助下，你已经得知有$m$个字符串不可能是密码的子串，现在想让你计算出可能密码的总数。

密码只包含四个数，$0、1、2、3$

由于可能性会非常多，因此最后的答案需要取模$1000000007(1e9+7)$

# Standard Input

第一行：两个整数$n（1 \le n \le 2000000000）,m(0 \le m \le 10)$

接下来m行，每行有一个密码子串，密码子串的长度不超过10

# Standard Output

一个正整数，即满足条件的密码总数

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
<tr><td>5 4
00
11
22
33
</td><td>324</td></tr></table>


# Constraints



# Note



# Source


