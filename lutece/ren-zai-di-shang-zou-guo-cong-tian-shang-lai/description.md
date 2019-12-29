
# Content

`人在地上走，锅从天上来。`~~时臣出来背锅~~

有一天，天上突然掉下来好多黑锅~~然而这并不重要~~，我们不妨假设地面是一条$X$轴的直线，每次黑锅也会呈一条直线掉下来，但是黑锅是可以覆盖的，比如在$x = 3$这个位置有个黑锅，但是如果又有一个黑锅掉在$x=3$，那么新的黑锅就覆盖了旧的黑锅，就变成了一个黑锅。我们把一个不与其他黑锅相连接的线段叫做一个*黑锅联通块*。比如现在有一个联通块覆盖的区间是$[a,b]$，另外一个联通块覆盖的区间是$[c,d]$，当且仅当$a > d$或者$c > b$时我们认为这是两个联通块，如果有相交部分，我们认为这是一个联通块，并且覆盖的区间分别为$[min(a,c), max(b,d)]$。现在天上会掉下来$n$次黑锅，对于每次掉下来的一整片黑锅，你都得回答覆盖后地面上有多少个黑锅联通块。

# Standard Input

第一行一个*n*

随后 *n* 行每行两个数，分别是$l, r$

# Standard Output

对于每对$l$和$r$，只需要输出有多少个黑锅联通块就行了。

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
1 3 
4 5 
2 4 </td><td>1 2 1</td></tr></table>


# Constraints

$$1\leq n \leq 1e5$$

$$1\leq l \leq r \leq 1e9$$

# Note

第一次落下时覆盖了区间$[1,3]$，所以答案为1。

第二次落下时覆盖了区间$[4,5]$，所以答案为2。

第三次落下时覆盖了区间$[2,4]$，所以将$[1,3]$和$[4,5]$两个区间连在了一起，答案为1。

# Source


