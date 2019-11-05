
# Content

咕之大，一锅炖不下。

咸鱼决定背着锅去找咕咕啦！

现在在地图上标记了 $n$ 个点，咸鱼一共有 $m$ 个锅，每个锅上有两个柄，分别写着 $u$ 和 $v$。每一个锅除了可以炖咕咕之外，还可以让咸鱼在锅的柄上两个数字所代表的点之间跳一次。比如，如果咸鱼在点 $u$，他使用一个写着 $(u,v)$ 的锅，那么他可以用这个锅跳到点 $v$。当然，顺序是没有关系的，转一下就好了。每个锅用过一次后就不能再用了（既不能跳跳，也不能炖咕咕）。

咕咕说：怎么能让咸鱼背锅！于是，咕咕决定了在咸鱼用完那堆锅绝！不！现！身！

现在咕咕问你，有没有办法在地图上找到一条咸鱼路径，使得咸鱼用(shuai)完那堆锅。

# Standard Input

第一行两个数字：$n,m(2\le n \le 10^6,n-1 \le m \le \min( \frac{n\times (n-1)}{2} , 2\times 10^6) )$

接下来 $m$ 行，每行两个数字 $u,v(0\le u,v < n)$，代表每个锅的柄上的两个数字。一行中两个数字均不相同，且每一行的两个数字组成的集合也不相同。

（输入保证两两点之间都存在一堆锅使得咸鱼可以相互到达）

（点的下标从 $0$ 开始）

# Standard Output

如果不能找到咸鱼路径，则输出 `No` 即可。

如果可以找到咸鱼路径，输出两行。

第一行输出 `Yes`。

第二行输出 $m+1$ 个数，代表咸鱼路径，第一个数为咸鱼的起点，最后一个数为咸鱼的终点，相邻的两个数 $u_i,u_{i+1}$ 表示咸鱼在 $u_i$ 点时使用了锅柄上写着 $(u_i,u_{i+1})$ 或 $(u_{i+1},u_i)$ 的锅到达了 $u_{i+1}$ 点。

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
<tr><td>3 2
0 1
0 2</td><td>Yes
2 0 1</td></tr><tr><td>4 3
0 1
0 2
0 3</td><td>No</td></tr></table>


# Constraints



# Note

你们以为不用锅咸鱼也会走吗？

不可能的。

# Source


