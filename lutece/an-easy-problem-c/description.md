
# Content

N个数排成一列，有三种操作。1.给一段区间内的每个数乘上一个非负整数。2.给一段区间内的每个数加上一个非负整数.3.询问一段区间的和模上P的值。

# Standard Input

第一行两个整数N(1≤N≤100000)表示数的个数,P（1≤P≤1000000000）表示模的值。接下来一行N个整数ai(0≤ai≤1000000000),接下来一行一个整数M(1≤M≤100000)表示操作数量，接下来M行每行描述一个操作。第一种操作描述：1 L R C（0≤C≤1000000000）,表示把L到R这段区间每个数乘上一个C。第二种操作描述：2 L R C（0≤C≤1000000000）,表示把L到R这段区间每个数加上一个C。第三种操作3 L R 表示询问L到R这段区间内的数的和模上P的值。

# Standard Output

对面每个询问，输出对应的答案，每个询问占一行。

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
<tr><td>7 43
1 2 3 4 5 6 7
5
1 2 5 5
3 2 4
2 3 7 9
3 1 3
3 4 7</td><td>2
35
8</td></tr></table>


# Constraints



# Note



# Source


