
# Content

普通的魔法使魔理沙又开始了新的一轮修行计划。

为了提升自己的魔力和强化迷你八卦炉，魔理沙需要从魔法蘑菇中获取魔力。

现在魔理沙一共有$n$个蘑菇，分别编号为$1-n$，第$i$个蘑菇初始魔力强度为$a\_i$。

魔理沙可以用八卦炉对某个区间内的蘑菇进行充能，使它们的魔力都得到一定的增幅$x$。

然后魔理沙偶尔也想知道，某个区间内，魔力最充裕的蘑菇有多少魔力。以此来估算自己什么时候可以打败灵梦。

但魔理沙突然想骑着扫帚去魔法之森里看望爱丽丝，所以她把八卦炉留给了你，现在任务就落到你的头上了。

# Standard Input

第一行一个整数$n$（$n\leq 10^6$），代表蘑菇数量。

第二行$n$个整数，分别是$a\_i$.($a\_i\leq 10^6$)

第三行一个整数$q$，表示有$q$个询问($q\leq 10^5$)

接下来$q$行，

每行先是一个整数$t$，代表这是$t$操作。

如果$t=0$，接下是三个整数，$l,r,x$，表示$[l,r]$区间都增幅魔力$x$

如果$t=1$,接下来是两个整数，$l,r$，表示询问$[l,r]$区间内蘑菇的魔力最大值

# Standard Output

针对每个$t=1$的询问输出答案。

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
1 2 3 4 5
3
1 1 5
0 2 3 10
1 3 5</td><td>5
13</td></tr></table>


# Constraints



# Note



# Source


