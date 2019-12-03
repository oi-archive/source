
# Content

cxx读了“守株待兔”的寓言故事深受启发，常年在森林里活动的她决定以守株待兔作为捕获兔子的方式，她已经想好了今晚上的晚饭——冷吃兔。cxx现在要放置一些木桩，森林里有$n$个点可以放置木桩，有一些兔子会出现在以这$n$个点中两个不同点为端点的$m$条道路上，因为这是属于cxx的世界，所以一旦道路的某一端有一个木桩，那么出现在这条道路上的兔子都会往上撞。因为cxx希望能吃到非常多的冷吃兔，并且又不希望太累，所以她希望放置最少的木桩，使得所有道路上的兔子都能撞到木桩上，被捕获。

并且因为cxx常年在森林里活动，她发现这$n$个点可以分为左右两部分，每条道路都有一端在左边，一端在右边

# Standard Input

第一行三个正整数$a,b(a+b \leq 100000)，m(\leq 300000)$分别表示左边和右边可以放木桩的点数，和道路的数量

接下来$m$行每行两个整数$u,v$表示从左边的点$u$到右边的点$v$有一条道路$(1\leq u,v\leq n)$

可能会出现重边

# Standard Output

一行一个整数表示cxx需要放置的最少木桩数量

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
<tr><td>3 3 7
1 1
1 2
2 2
2 3
3 1
3 2
3 3
</td><td>3</td></tr></table>


# Constraints



# Note

一种合法的方案是在节点1,2,3分别放置一个木桩

# Source


