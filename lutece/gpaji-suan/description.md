
# Content

G.P.A.(`Grade Point Average`)即成绩点数与学分的加权平均值。
GPA一般用4分制（`4.00 scale`）计算，换算方法参见下表： 

|百分制分数|等级|成绩点数|
|--------------|------|-----------|
|90-100|A|4|
|80-89|B|3|
|70-79|C|2|
|60-69|D|1|
|60以下|E|0|

例如某同学三门课程的学分和成绩为：
* A课程4个学分，成绩92（A）
* B课程3个学分，成绩75（C）
* C课程5个学分，成绩80（B）

$GPA = \frac{4\times 4 + 2\times 3 + 3\times 5} {4 + 3 + 5} = 3.08$

# Standard Input

输入第一行为整数$N$($1\leq N\leq 10$)，表示有$N$门课程。

以下$N$行每行为两个整数$C$, $S$ ($1\leq C\leq 5$, $0\leq S\leq 100$)表示该门课程的学分和成绩。

# Standard Output

输出仅一个小数$g$，表示该同学的GPA，结果保留$2$位小数

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
4 92
3 75
5 80</td><td>3.08</td></tr></table>


# Constraints



# Note



# Source


