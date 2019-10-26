
# Content

富庶的建业城中，有一条格格不入的长街，名曰跳蚤街，被战争所致的孤儿，聚集于此。全国的经济都在为战争服务之时，也无人顾得了这里了。

除了两位夫人。

大乔小乔每天都会带着一些食物来到跳蚤街，分给某一位孩子。为了避免分配不均，她们时常会询问一个区域内食物的总量，然后进行调整以保证每个孩子都有足够的食物。

# Standard Input

第一行两个整数$n$，$m$，表示跳蚤街住着$n$户孩子，大乔小乔一共分发或询问了$m$次。

第二行$n$个整数，第$i$个数$a\_i$表示第$i$户孩子已有$a\_i$的食物。

接下来$m$行，每行开始先读入一个整数$s\_i$，指明这是一次询问还是一次分发。

$s\_i = 0$，表明这是一次询问，然后读入两个整数$l\_i,r\_i$，表示询问$[l\_i，r\_i]$区间中的孩子们一共有多少食物。

$s\_i = 1$，表明这是一次分发，然后读入两个整数$x\_i,w\_i$，表示对第$x\_i$户孩子分发了$w\_i$的食物。

$1\leq n,m\leq100000,0\leq a\_i \leq 100000,1\leq x\_i \leq n ,0 \leq w\_i \leq 10000,1\leq l\_i \leq r\_i \leq n$

# Standard Output

有多少询问就输出多少行，每行输出一个整数，作为对该询问的回答。

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
<tr><td>5 4
1 2 3 4 5
1 2 3
0 2 4
1 4 1
0 1 5</td><td>12
19</td></tr></table>


# Constraints



# Note



# Source


