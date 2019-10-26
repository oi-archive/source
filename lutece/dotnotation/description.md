
# Content

love8909最近在学一种新的表达式表示法，称之为`<DotNotation>`。定义如下：

* `<DotNotation> := <Number> | <DotNotation><Dots><Operator><Dots><Number>`
* `<Dots> := "" | <Dots>"."`
* `<Operator> := exactly one of "+-*/"`
* `<Number> := exactly one of "0123456789"`

这是一个递归的定义，即是说：
* 单个的数字是`<DotNotation>`
* 在`<DotNotation>`后连接任意数量的`.(<Dots>)`，然后连接一个操作符`<Operator>`，再接上任意数量的`.`，最后再接一个数字，得到的还是还是一个`<DotNotation>`
* 比如说，`5`是一个`<DotNotation>`，如果在后面接上`.+.7`，你将得到另一个`<DotNotation>`， 如果你再在后面接上`*..3`得到`5.+.7*..3`，这还是一个`<DotNotation>`

可是love8909很纠结，因为他竟然不会判断一个`<DotNotation>`是否合法，你能帮帮他吗？

# Standard Input

第$1$行一个数$T$，表示测试数据组数。

后面$T$行每行一个长度为$L$的字符串($1 \leq L \leq 50$)。

# Standard Output

$T$行，每一行，如果合法，输出`Yes`，反之输出`No`。

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
<tr><td>5
3+5
9..+.5...*....3
5.3+4
9*9*9*9*9*9*9*9*9*9*9*9*9*9
3.........../...........4</td><td>Yes
Yes
No
Yes
Yes</td></tr></table>


# Constraints



# Note



# Source


