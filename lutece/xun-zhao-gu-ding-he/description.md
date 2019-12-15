
# Content

有两个数组$x$与$y$，各有$m$与$n$个元素，而且各个元素没有依顺序排列；$d$是一个已知的值。请写一个程序，看看在$x$与$y$中有没有满足$x_i+y_j=d$的元素。

# Standard Input

本题有多组输入数据。第一行是输入数据的组数$T$，每组数据占三行，第一行是三个用空格隔开的数$m$、$n$和$d$，表示下面两行$x$和$y$数组的元素个数依次为$m$和$n$个，以及固定和$d$。紧接着两行分别是$m$和$n$个元素，每个元素后均有一个空格。$1\le T\le 20$，$1\le m,n\le 1000$。

# Standard Output

对应每组数据，输出可能有多行，如果没有找到，输出为`nothing`，如果输出有多行，应先按$x$的下标从小到大输出，若$x$的下标相同，则按$y$的下标从小到大输出。详细可参看样例。

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
4 4 9
3 7 2 4 
2 5 2 3 
4 3 15
1 2 3 4 
5 8 6</td><td>case 1:
x[1]+y[0]=9
x[1]+y[2]=9
x[3]+y[1]=9
case 2:
nothing</td></tr></table>


# Constraints



# Note



# Source


