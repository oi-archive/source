
# Content

已知一个已经从小到大排列好的数组，所谓这个数组中的一个平台，就是连续的一串值相同的元素，并且这一串元素不能再延伸。例如，在$1,2,2,3,3,3,4,5,5,6$中$1$、$2,2$、$3,3,3$、$4$、$5,5$、$6$都是平台。试编写一个程序，接收一个数组，输出这个数组中所有平台和最长平台的个数与长度。

# Standard Input

本题有多组输入数据。第一行是输入数据的组数$T$，每组数据有两行，第一行是一个整数$n$，表示下一行有$n$个数据输入，每个输入数据后有一个空格。$1\le T\le 20$，$1\le n\le 1000$。

# Standard Output

对应每组数据，应输出两行，第一行是两个用空格隔开的数（注意该行尾没有空格），第一个数表示最长平台的个数，第二个数表示最长平台的长度，第二行是所有的平台，平台应按在数组中出现的顺序输出，最后一个平台后没有空格。

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
<tr><td>1
10
1 2 2 3 3 3 4 5 5 6</td><td>1 3
{1},{2,2},{3,3,3},{4},{5,5},{6}</td></tr></table>


# Constraints



# Note



# Source


