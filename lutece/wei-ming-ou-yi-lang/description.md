
# Content

苇名欧一郎踏上了复兴苇名的道路,在复兴苇名的路上,oy需要按照一定的顺序击败n个敌人.欧阳在每消灭一个敌人之后可以获得一个新武器(例如不死斩),而且某些敌人也只有用特殊的武器才能被消灭(比如附虫者只有不死斩可以斩杀).现在oy想知道他有多少种不同的顺序来消灭这些敌人.

# Standard Input

输入包含多组测试数据,第一行为一个整数T,代表总测试数.
接下来一行为一个整数n,代表敌人总数
接下来一行为一个长度为n的01串s,代表欧阳之力(即oy在没有任何武器时可以消灭的敌人) , $s_i$为1代表可以消灭第i个敌人,为0则不能
接下来n行依次描述消灭第i个敌人之后获得的新武器,描述方式与"oy之力"相同

# Standard Output

对于每组数据,按照Case kase: ans的格式输出顺序总数,其中kase指当前是第kase组测试数据

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
<tr><td>3 
1 
1 
1

2 
11 
01 
10 

3 
110
011 
100 
000</td><td>Case 1: 1 
Case 2: 2 
Case 3: 3</td></tr></table>


# Constraints

$1 \leq T \leq 50$

$1 \leq n \leq 16$

# Note



# Source


