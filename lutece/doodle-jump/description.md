
# Content

给你四个数,a,n,p,h，其中gcd(a,p)=1,现在你有0,a,2a,3a,4a,...,na，把这n+1个数模p之后排序之后，问两两之间差值是不是都小于等于h，如果是输出YES，否则输出NO

# Standard Input

第一行给出一个整数T，表示数据组数  
接下来T行，每行四个整数表示a,n,p,h

# Standard Output

对于每一组数据，输出一行，YES或者NO

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
7 4 12 2
7 1 9 4
7 4 12 3</td><td>NO
NO
YES</td></tr></table>


# Constraints



# Note

10%的数据 $T=1$  
10%的数据 $n=100000$  
100%的数据 $T\le10000,1\le a\le 10^9,1\le n<p\le 10^9,0\le h\le 10^9$

# Source


