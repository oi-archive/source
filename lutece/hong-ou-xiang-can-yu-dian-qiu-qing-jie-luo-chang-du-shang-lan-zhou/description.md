
# Content

考试结束后，为了证明自己才是最蒻的，同学们纷纷去找老师查分阅数—哦不—是查阅分数。    

可老师担心学生知道自己的成绩会伤心，于是只告诉学生这样的信息：    

$\;\;\;\;\;\;$**编号为 $u$ 的学生分数比编号为 $v$ 的学生分数高 $w$ 分甚至更多。**     

知道这些信息后，同学们想知道自己分数可能的 **最小值** 和 **最大值** 。不过老师记性不太好，给出的信息可能有误。

# Standard Input

第一行两个整数 $n$ 和 $m$，表示学生个数和老师给的信息数。

接下来 $m$ 行每行三个整数 $u$ 、$v$ 和 $w$，含义如上文所描述。

学生从 $1$ 到 $n$ 编号，学生的分数为 $0$ 到 $100$ 之间的整数。

$1 \leq n \leq 100000$，$1 \leq m \leq 1000000$，$1 \leq u$ 、$v \leq n$，$0 \leq w \leq 100$ 。

# Standard Output

若老师给出的信息有误，仅输出一行 $-1$ 。

否则输出 $n$ 行，第 $i$ 行为以空格隔开的两个整数，分别表示编号为 $i$ 的学生的分数可能的 **最小值** 和 **最大值** 。

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
<tr><td>2 2
1 2 1
2 1 1</td><td>-1</td></tr><tr><td>3 2
1 2 1
2 3 1</td><td>2 100
1 99
0 98</td></tr></table>


# Constraints



# Note



# Source


