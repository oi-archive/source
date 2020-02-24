
# Content

给你一个大小为$n$的集合$S$，集合里有$n$个互不相同正整数.   
有$q$个询问，每次询问是否能选择$S$中的一些数字（**同一个数字可以选择多次,也可以任何数字都不选**），使它们相加的和为$m$.

# Standard Input

第一行一个数$n\left (1 \leq n \leq 2000  \right )$,表示集合$S$的大小.  
第二行$n$个数，第$i$个数$a_{i}\left (1 \leq a_{i} \leq 50000 \right )$表示集合$S$中的第$i$个数.                    
第三行一个数$q\left (1 \leq q \leq 10000  \right )$，表示询问次数.  
接下来$q$行，每行一个数$m\left (0 \leq m \leq 1000000000 \right )$，表示该次询问的数.

# Standard Output

每次询问输出一行,如果存在和为$m$的方法，输出 `YES`,否则输出 `NO`.

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
2 4 9
4
6
7
18
25</td><td>YES
NO
YES
YES
</td></tr></table>


# Constraints



# Note

对于第一个询问，存在$2+2+2=6$,所以输出 `YES`  
对于第一个询问，无法构造，输出 `NO`    
对于第三个询问，存在$9+9=18$,所以输出 `YES`    
对于第四个询问，存在$2+2+4+4+4+9=25$,所以输出 `YES`

# Source


