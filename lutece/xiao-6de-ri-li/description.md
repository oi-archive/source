
# Content

某日，love8909闲得无聊，就摆弄起他的小6(Nokia 6120c)来，他发现小6的日历如右图所示。

日历中深色标记的格子（右图的16号）为当前位置；按上、下、左、右键可以移动到相邻的格子；特别的，在某行最后一个格子按右键可移动到下一行第一个格子，反之，在某行第一个格子按左键可移动到上一行最后一个格子。

现在love8909想知道，给定同年同月的两天，从其中一天移动到另外一天至少需要按几次键？（要求整个移动过程不超出当前月份）

已知1900年1月1日为星期一。

# Standard Input

输入包含多组测试数据。

第一行为一个整数$T$ ($T\leq 50000$)，代表测试数据组数。

以下$T$行，每行两个日期，用单个空格分隔，日期格式为`yyyy-mm-dd`，依次代表年、月、日，($1900\leq yyyy\leq 2012$ , $mm > 0$, $dd > 0$）。

数据保证每行所给的日期是同年同月的。

# Standard Output

每行输出一个整数$d$，代表最少需要的按键次数。

如果询问的日期不存在，输出`-1`。

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
1989-09-02 1989-09-23
2012-11-30 2012-11-31</td><td>3
-1</td></tr></table>


# Constraints



# Note



# Source


