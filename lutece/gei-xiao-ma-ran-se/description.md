
# Content

小兔子是坏小兔子，因为他总会在上课的时候选择摸鱼。

今天上课，小兔子又发现了一款神奇的游戏。

游戏是创造类型的，每一关卡都会给你 $n$ 只马，小兔子会给每一只马涂上颜色，黑色或者白色，其中会有 $m$ 对马会生出小马，会有以下三种情况：
1. 黑马与黑马会生出小黑马；
2. 白马与白马会生成小白马；
3. 黑马与白马会生成小斑马。

 
不要问我为什么能生出小斑马，也不要问我怎么生出小马的，我不知道我不知道......

小兔子不想看到在小马中看到小黑马，那么小兔子一共有多少种涂色方式呢？

# Standard Input

第一行两个数 $n,m$，表示 $n$ 只马、$m$ 对关系。
接下俩 $m$ 行，每一行两个数 $a, b$，表示第 $a$ 只马和第 $b$ 只马会生出一个小马。

# Standard Output

输出一个整数，代表答案。

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
<tr><td>3 3
1 2
1 3
2 3</td><td>4</td></tr></table>


# Constraints

$1\leq n\leq 40, 0\leq m \leq \frac{n(n-1)}{2}$
$1\leq a, b\leq n\ (a \neq b)$

# Note



# Source


