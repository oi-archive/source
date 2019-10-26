
# Content

在足球比赛中，有不少赛事，例如世界杯淘汰赛和欧洲冠军联赛淘汰赛中，当比赛双方经过正规比赛和加时赛之后仍然不分胜负时，需要进行点球大战来决定谁能够获得最终的胜利。点球大战的规则非常简单，两方轮流派出球员罚点球，每方各罚$5$个。当$5$轮点球结束以后如果仍然不分胜负，则进入一轮定胜负的阶段。两方各派一名球员罚点球，直到有一方罚进而另一方没有进为止。

在北美职业冰球联赛中，也有点球大战。与足球的规则不同的是，它只先罚$3$轮点球，随后就进入一轮定胜负的阶段，而其他的规则完全一样。

在本题中，输入将给出每次点球是否罚进，而你的任务则是输出一个`比分板`。

# Standard Input

输入包含多组数据。每组数据的第一行包含一个整数$N$($1 \leq N \leq 18$)，表示双方总共罚了多少个点球，$N=0$表示输入结束。随后有$N$行，每行是一个如下形式的字符串：

`XXXX good`：表示这个点球罚进

或者`XXXX no good`：表示这个点球没有罚进

其中`XXXX`表示球员名字（全部由字母和空格组成，保证不会出现歧义）

每一行保证不超过$100$个字符。

`XXXX`和`good`以及`XXXX`和`no`、`no`和`good`之间保证有且只有1个空格。

`good`、`no good`都是小写。本题是大小写相关的。

数据不保证点球大战一定结束，也不保证在结束以后立即结束这组数据（即：不用判断点球大战是否结束，只用把罚进的点球往比分上加即可）。

# Standard Output

对每组数据，输出一个比分板。一个点球如果罚进，则在对应的地方标上`O`，如果没有进则标上`X`。先罚球的队伍的信息在上面，后罚的在下面。最右边标上两队的比分。具体格式参考样例输出。注意如果一轮点球只罚了一个，则后面那个点球对应的地方写上`-`。

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
<tr><td>6
Riise good
Ballack good
Gerrard no good
Lampard no good
Fernando Torres good
Malouda good
9
Christiano Ronaldo no good
Messi no good
Giggs good
Abidal no good
Carrick good
Ronaldinho good
Rooney good
Henry no good
Tevez good
0</td><td>1 2 3 Score
O X O 2
O X O 2
1 2 3 4 5 Score
X O O O O 4
X X O X - 1</td></tr></table>


# Constraints



# Note

空格数要和样例输出一样，否则很可能会被判为格式错误`Presentation Error`。

# Source


