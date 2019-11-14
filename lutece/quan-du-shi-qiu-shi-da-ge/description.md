
# Content

秋实大哥是一个多愁善感的人，偶尔也会唱唱两句伤情的歌。每次唱完后，秋实大哥都能解决一道问题！这次也不例外。

秋实大哥告诉了你 一些关于这个问题的信息

>#####如果一个字符串$S$是由若干个子串$a$连续拼接而成的，则称$a$是$S$的循环节，即$A=a+a+...+a$。比如 aba 是 abaabaaba 的循环节。
>#####一个字符串可能存在多个循环节，比如 aaaaaaaa ，含有4个循环节，分别是 a ， aa ， aaaa ， aaaaaaaa 。很显然，一个字符串是其本身的循环节。在这4个循环节中，长度最小的是"a"，所以"a"是$S$的最小循环节。
>#####字符串所有循环节里长度最小的循环节，就是该字符串的最小循环节。
>#####一个长度为$N$的字符串，含有$N$个非空前缀。定义$P(i)$表示$S$的第$i$个非空前缀$(0 \leq i<|S|)$，$P(i)=S_{012...i}$。比如"abcde"含有5个非空前缀，分别是"a"，“ab”，“abc”，“abcd”，“abcde”。

####现给一个字符串$S$，请先按顺序输出$S$的每一个非空前缀的最小循环节的长度，然后，再输出$S$的最小循环节。

秋实大哥唱完了，问题也解决了，现在他请你来解决这个问题。

# Standard Input

第一行输入一个字符串$S$（$0<|S| \leq 3\cdot 10^6$），$S$只含有小写英文字母（a－z）

# Standard Output

第一行输出 $|S|$ 个数，分别表示$S$的每一个非空前缀的最小循环节的长度，每两个数用一个空格隔开，最后一个数后面不要有空格。

第二行输出一个字符串，表示$S$的最小循环节。

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
<tr><td>ab</td><td>1 2
ab</td></tr><tr><td>aaaaaaaaa</td><td>1 1 1 1 1 1 1 1 1
a</td></tr><tr><td>aaaaaaaad</td><td>1 1 1 1 1 1 1 1 9
aaaaaaaad</td></tr><tr><td>abbaaddaabbaadda</td><td>1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 8
abbaadda</td></tr><tr><td>abbaabbaabbaabba</td><td>1 2 3 4 5 6 7 4 9 10 11 4 13 14 15 4
abba</td></tr></table>


# Constraints



# Note



# Source


