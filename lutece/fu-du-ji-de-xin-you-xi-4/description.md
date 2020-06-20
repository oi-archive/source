
# Content

今夜，狂欢夜，复读机要反击了。

子弹？复读机们拉来了意大利炮！

群管理现在面对着一个长度为 $n$ 的小写字母组成的串 $s$，以及 $q$ 颗炮弹。

每颗炮弹上标着两个数 $l,r$ ，其威力为其子串 $s[l\ldots r]$ 的所有可能被复读的长度之和。（例如`aba `可能被复读长度为 $2$ 或 $3$）

群管理只有猜对每颗炮弹的威力才能抵御下这些炮弹，作为临时管理员，你要帮忙抵御下这些子弹。

准备迎敌吧！阿 sir！

# Standard Input

第一行一个长度为 $n$ 的字符串 $s$。
第二行一个数，表示有 $q$ 颗炮弹。
接下来 $q$ 行，每行两个整数 $l$, $r$。

# Standard Output

输出 $q$ 行，每行一个整数，表示炮弹的威力。

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
<tr><td>aaaa
4
1 1
1 2
1 3
1 4</td><td>1
3
6
10</td></tr></table>


# Constraints

$1\leq n,q \leq 100000$
$1\leq l, r \leq n$

# Note

第一组询问，子串为`a`，有周期 $1$（即被复读长度可能为 $1$），所以答案为 $1$。
第二组询问，子串为`aa`，有周期 $1,2$（即被复读长度可能为 $1,2$），所以答案为 $1+2=3$。
第三组询问，子串为`aaa`，有周期 $1,2,3$（即被复读长度可能为 $1,2,3$），所以答案为 $1+2+3=6$。
第四组询问，子串为`aaaa`，有周期 $1,2,3,4$（即被复读长度可能为 $1,2,3,4$），所以答案为 $1+2+3+4=10$。

# Source


