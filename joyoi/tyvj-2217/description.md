# 

 
 # 题目描述 
<p>
给定一棵树，则我们就可以得到它的BFS序列和DFS序列。所谓BFS序列，就是从根节点开始扩展，深度小的优先，对同一个节点若干个儿子，编号小的优先扩展；所谓DFS序列，就是从根节点开始，深度大的优先，对同一个节点若干个儿子，编号小的优先扩展。<br>现在的问题是，给定一棵树的BFS序列和DFS序列，请你算出有多少棵树满足条件。<br></p> 

 
 # 输入格式 
<p>
第一行包含一个整数N，表示树中节点的个数。第二行中包含N个整数，表示一棵树的BFS序列。第三行中同样包含N个整数，表示这棵树的DFS序列。我们保证输入数据至少对应了一颗树。<br><br></p> 

 
 # 输出格式 
<p>
仅包含一个整数，表示满足条件的树的个数。<br></p> 

 
 # 提示 
<p>
1 ≤ N ≤ 10000</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4
1 2 3 4
1 2 3 4
</td><td>
4</td></tr></table>
