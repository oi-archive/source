
# Content

第六次上机有$6$个题目，题号分别是`1038`、`1039`、`1040`、`1041`、`1042`和`1043`。每个同学都在认真的做。但依然有些同学过的题多，有些同学过的少。有的同学虽然题未过，但程序写出来，也进行了提交。为了了解本次上机的情况，老师规定：
1. 如果该题一次`Accepted`(即第一次就通过)，则积分$100$，否则$95$；
2. 如果该题`Presentation Error`，则积分$90$；
3. 如果该题`Wrong Answer`，则积分$70$；
4. 如果该题`Compile Error`，则积分$50$。
5. 每人每题只计算一次，按最高值计算。

本题假设：题目提交返回类型只有`Accepted`、`Presentation Error`、`Wrong Answer`和`Compile Error`四种。每个同学每次提交的程序都保存在一个文件中，文件的后缀名为`c`和`cc`，文件名的格式为：
`RunID_AuthorID_返回类型_题号.后缀名`，比如：`6890_2910201012_Accepted_1039.cc`

# Standard Input

本题只有一组输入数据。第一行是文件名称的数目$T$，下面是$T$行文件名。`RunID`不超过整数的范围，`AuthorID`的长度不超过$50$个字符，$T$不超过$2000$。

# Standard Output

输出有多行，每行对应一个`AuthorID`（即一个`AuthorID`只有一行），其后是积分，用空格隔开，最后一行后有一个空行。注意要先按`AuthorID`从小到大排序（按字符的ASCII码）。

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
6855_Tommy_Wrong Answer_1038.cc
7036_2910201009_Compile Error_1038.cc
6915_Tommy_Accepted_1039.cc</td><td>2910201009 50
Tommy 170</td></tr></table>


# Constraints



# Note



# Source


