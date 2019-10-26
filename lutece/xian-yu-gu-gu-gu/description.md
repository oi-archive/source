
# Content

`咸鱼`有个咕咕笼。

咕咕笼可以划分成$m \times n$个格子，每个小格子可以放下一只`咕咕`，也可以放下一个咕咕槽。

现在咕咕笼里有若干只`咕咕`。

放在咕咕笼里的`咕咕`能够看到他上下左右四个方向上的所有格子。

当然，因为咕咕槽比较高，那群`咕咕`没办法看见咕咕槽后面的`咕咕`。

`咸鱼`发现如果两只`咕咕`能够看见对方，他们会在咸鱼离开的时候跑在一起形成更大的`咕咕咕咕`，否则他们只会像条咸鱼一样安心待在那里咕咕。

现在`咸鱼`不希望他们形成`咕咕咕咕`，需要带走一些`咕咕`。

但是带走太多的`咕咕`会让`咸鱼`咕咕咕咕。

`咸鱼`希望你能帮他决定至少应该带走多少只`咕咕`。

<img src="http://chuantu.biz/t6/313/1526656579x-1404793178.jpg" width = "400" />

# Standard Input

第一行两个整数$m$,$n$。$(1\le m,n \le 50)$

接下来$m$行，每行一个字符串，含有$n$个字符。

第$i$个字符串第$j$个字符表示了咕咕笼第$i$行第$j$列的情况。

若字符为`o`，表示这上面有只`咕咕`。

若字符为`+`，表示这上面有个咕咕槽。

若字符为`.`，表示上面既没有`咕咕`，也没有咕咕槽。

# Standard Output

输出`咸鱼`至少应该带走多少只`咕咕`。

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
o+
.o</td><td>0</td></tr><tr><td>2 5
o+.o+
.o..o</td><td>1</td></tr><tr><td>1 1
.</td><td>0</td></tr></table>


# Constraints



# Note

Sample 1: 不需要带走`咕咕`。

Sample 2: 至少需要带走$(2,2)$或$(2,5)$其中一只`咕咕`，不然他们会在`咸鱼`离开后变成`咕咕咕咕`。

Sample 3: 没有`咕咕`可带。

# Source


