
# Content

王征战回来了，为了庆祝胜利，王准备请大家吃饭！

于是n个人来到了一家豪华餐厅，这家餐厅有一张长————————长的桌子，每个人只能坐在桌子的南北两侧

一行人中，有p对A关系，m对B关系，如果u和v有A关系，则u和v必须坐在不同侧，如果u和v有B关系，则u和v必须坐在同侧

如果一种座位安排既满足所有A关系也满足所有B关系，则这种安排是和谐的。

王将会选一侧坐下，然后其他人再坐下，现在王想知道，是否存在一种和谐的座位安排。

# Standard Input

第一行是描述中的三个整数n，p，m$(2\leq n\leq 10^4, 0\leq p\leq 10^4, 0\leq m\leq 10^4)$

接下去n行每行一个字符串，表示参加宴会的人的名字，字符串保证不重复，不含空格且长度不超过10。

接下去p行每行两个字符串x和y，表示x和y具有A关系，x和y用空格隔开

接下去m行每行两个字符串x和y，表示x和y具有B关系，x和y用空格隔开

最后一行一个字符c，c=N表示王坐在北侧，c=S表示王坐在南侧

王的名字总是`King`

# Standard Output

如果存在和谐的座位安排，则第一行输出`Yes`

然后接下去n行每行一个字符串s和大写英文字母c，表示名字为s的人坐的位置，c=N表示坐在北侧，c=S表示坐在南侧

座位安排可以按任意次序输出

如果不存在这样的座位安排，输出`No`

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
<tr><td>4 3 1
King
A
B
C
A B
B C
A C
King A
N</td><td>No</td></tr><tr><td>4 3 1
King
A
B
C
A B
A C
King A
B C
N</td><td>Yes
King N
A S
B N
C N</td></tr></table>


# Constraints



# Note



# Source


