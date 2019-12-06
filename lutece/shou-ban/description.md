
# Content

阿O,你又在打电动哦
被阿嫲训斥的oy无奈只能放下电脑,回到自己的房间去整理自己的手办们.
富可敌国的oy买了n个手办,放在自己的柜子里,第i个手办的高度为$h_i$.
阿嫲总是觉得oy的手办们摆放的很混乱,她对混乱值的定义如下,连续的高度相同的所有手办看作一个片段,手办们的混乱度就是所有手办的片段数.

例如五个手办的排列: 114514,114514,114515,114515,114516的混乱程度为3.但114514,114515,114514,114515,114514的混乱程度为5.

oy很懒,所以他最多只会从n个手办中抽出k个手办,然后再将这k个手办插回去(其他手办的先后顺序必须保持不变).
oy想知道这样整理出来的手办们的最小混乱度是多少

# Standard Input

输入包含很多组测试数据.
每组数据第一行为两个整数n,k.含义如上述.
第二行包含n个整数$h_i$,即初始时从左到右每个手办的高度.
输入以n=k=0结束

# Standard Output

对于每组数据,输出手办们的最小混乱值

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
<tr><td>9 6
114518 114520 114514 114520 114515 114521 114515 114519 114516 
3 1
114516 114514 114518 
2 2
114521 114521 
6 3
114515 114520 114521 114518 114521 114515 
0 0</td><td>Case 1: 7

Case 2: 3

Case 3: 1

Case 4: 4</td></tr></table>


# Constraints

$1 \leq k \leq n \leq 100$
$114514 \leq h_i \leq 114521$

# Note



# Source


