
# Content

读入一组学生的成绩（成绩为百分制，均为整数，人数不超过$1000$人），查找给定成绩区间内的学生人数。

# Standard Input

输入第一行是整数$T$，表示后面测试数据的组数。对于每组数据，第一行是整数$n$，表示下面一行有$n$个$0$到$100$之间的整数（学生成绩）。再下一行是整数$m$（$m<30$），表示随后有$m$行整数，每行整数由两个整数$a$和$b$构成，$a$与$b$之间有一个空格，表示要查找的分数区间，且$a\leq b$。两组测试数据之间有一个空行。

# Standard Output

对于每一组区间，输出位于该区间学生的人数，占一行。在每组测试数组后输出一个空行。

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
<tr><td>2
10
12 67 87 100 0 45 88 99 97 67 
6
0 100
67 67
11 90
12 88
90 95
45 67

51
85 72 38 80 69 65 68 96 22 49 67 51 61 63 87 66 24 80 83 71 60 64 52 90 60 49 31 23 99 94 11 25 24 51 15 13 39 67 97 19 76 12 33 99 18 92 35 74 0 95 71 
3
33 39
32 37
45 57</td><td>10
2
6
6
0
3

4
2
5</td></tr></table>


# Constraints



# Note



# Source


