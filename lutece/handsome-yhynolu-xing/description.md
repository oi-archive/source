
# Content

<img src="/source/lutece/handsome-yhynolu-xing/img/aHR0cDovL2ltZzEuZ3RpbWcuY29tL2NvbWljL3BpY3MvaHYxLzI0MS8yMzkvMjE1NC8xNDAxMjUwMzYuanBn.jpg" width = "400" />

$TQL!!!$ 刷了一天的题后,集训队最 帅气/可爱 的$handsomeyhy$决定去春熙路散散步.

假设$handsomeyhy$初步计划了$N$个散步点,分别被标为$1,2,3...N$,这些点之间有$M$条道路.每条道路双向连接不同的两个点,且要走完这条道路会花费固定的时间.

初始时$handsomeyhy$在标号为$1$的点,她的最终目的地是标号为$N$的点.在这期间她可以穿过某个散步点(包括$N$)和通过某条道路任意次,一旦她决定走某条道路她会坚持把它走完(不能中途返回).

请问是否存在一种走法使得她恰好在$T$时间的时候在最终目的地呢?

# Standard Input

第一个数字$Case$表示样例数

对于每个样例
第一行三个数字$N$ $M$ $T$  表示有$N$个散步点 ($2 \le N \le 50$ ) $M$条道路 ($1 \le M \le 50$ ) 和时间$T$   ($1 \le T \le 1e18$ )

接下来$M$行 每行有$Ai$ $Bi$ $Ci$ 表示标号为$Ai$与$Bi$的两个不同点之间($1 \le Ai,Bi \le N$ )有一条道路 通过它一次需要$Ci$ ($1 \le Ci \le 10000$ )的时间.

# Standard Output

对于每个样例存在满足条件的走法则输出$Yes$ 否则输出$No$

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
3 3 25
2 3 5
1 2 6
1 3 7</td><td>Yes</td></tr></table>


# Constraints



# Note

$1到2$   $2到3$   $3到1$   $1到3$

# Source


