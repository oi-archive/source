
# Content

秋实大哥是一个儒雅之人，昼听笙歌夜醉眠，若非月下即花前。

所以秋实大哥精心照料了很多花朵。现在所有的花朵排成了一行，每朵花有一个愉悦值。

秋实大哥每天要对着某一段连续的花朵歌唱，然后这些花朵的愉悦值都会增加一个相同的值$v$($v$可能为负)。

同时他想知道每次他唱完歌后这一段连续的花朵的愉悦值总和是多少。

# Standard Input

第一行有一个整数$n$，表示花朵的总数目。

第二行包含$n$个整数$a_i$，表示第$i$朵花初始的愉悦值。

第三行包含一个整数$m$，表示秋实大哥唱了$m$天的歌。

接下来$m$行，每行包含三个整数$l$ $r$ $v$，表示秋实大哥对着$[l, r]$这个区间内的花朵歌唱，每朵花的愉悦值增加了$v$。

$1\leq n,m,a_i,|v|\leq 100000$，$1\leq l\leq r\leq n$。

# Standard Output

输出共$m$行，第$i$行表示秋实大哥完成第$i$天的歌唱后，那一段花朵的愉悦值总和。

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
0 0 0
3
1 2 1
1 2 -1
1 3 1</td><td>2
0
3</td></tr></table>


# Constraints



# Note



# Source


