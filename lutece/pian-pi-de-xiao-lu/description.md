
# Content

在电子科大清水河校区的某个偏僻角落里，有一条东西方向的小路，长L米（由西向东位置为$0$到$L$），小路上有$N$个人从$t=0$秒开始以相同的恒定速率$V$米/秒前进（面朝西或面朝东）。这条小路太偏僻了，所有人都想尽快离开这条小路。不幸的是，当两个人相遇时，只有男生会给女生让路（视为两人擦肩而过），男生遇上男生、女生遇上女生时，谁也不肯让路，只好都无奈的掉头往回走。

现在HS很好奇，想知道最后一个人离开小路的时间，以及所有人在小路上走的路程的总和，你能编写程序帮助他吗？

# Standard Input

第一行包括$3$个整数，$N$,$L$,$V$,表示小路上的人数、小路的长度、所有人前进的速率 ($N\leq 100,L\leq 1000000,V>0$)

接下来有$N$行，每行$3$个数据

第$i$行的数据表示第$i$个人的位置（从$0$到$L$的整数）、性别（`M`或`F`）、方向（`W`表示面朝西、`E`表示面朝东）

当$N=L=V=0$时，输入结束

# Standard Output

对于每组输入，输出一行两个小数，表示最后一个人离开的时间以及所有人在小路上走的路程的总和，用一个空格隔开，答案四舍五入保留两位小数

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
<tr><td>2 4 2
1 M E
3 M W
0 0 0</td><td>1.50 6.00</td></tr></table>


# Constraints



# Note



# Source


