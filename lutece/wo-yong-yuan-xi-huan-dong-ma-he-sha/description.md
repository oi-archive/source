
# Content

`梦里不觉秋已深，余情岂是为他人`。~~我永远喜欢冬马和纱~~

好了，上面都是废话，现在`Kazusa`又开始弹钢琴，Kazusa手速一如既往的快，瞬间就给出了$n$个音符，每个音符都有一个值$vi$，一旁的`北原春希`就在想，用一个区间的音符最少可以构成多少个*严格上升序列*~~因为数量少了丸户老贼就会让我春鸽去听音乐会~~。好了，问题来了，每次给定一个区间$[li, ri]$，问最少可以构成多少个严格上升序列。

~~只要你玩了冬马TE，你就能AK~~

# Standard Input

第一行一个$n$和$m$，表示音符数量和询问的区间数量。

接下来$n$个数，依次为$v1, v2 , v3, .... , vn$,表示每个音符的值。

再接下来$m$行每行两个整数$l, r$表示要询问的区间。

# Standard Output

输出$m$行。每行一个整数，表示每次询问的结果

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
<tr><td>6 4
6 7 8 2 3 8
3 3
4 5
1 4
2 2
</td><td>1
1
1
1
</td></tr></table>


# Constraints

$1 \leq n \leq 2e5$

$1 \leq m \leq 2e5$

$1 \leq vi \leq 1e9$

$1 \leq l \leq r \leq n$

# Note

比如现在区间$[l,r]$之间的数为$[1,2,3,2,1,3]$，那么最少可以构成$[1,2,3]$，$[1,2,3]$两个单调递增序列。答案为2。

# Source


