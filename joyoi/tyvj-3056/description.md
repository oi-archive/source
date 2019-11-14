# 

 
 # 题目描述 
<p>
在二叉搜索树中执行如下操作：<br>移除并输出所有叶子结点；<br>重复上述操作直到树为空。<br>如果在下图中执行上述操作，从左到右，过程如下： <br><img src="/source/joyoi/tyvj-3056/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA1Ni9wcm9ibGVtc19pbWFnZXMvMzY3Ny8xLmpwZw==.jpg"></img><br><br>依次输出的叶子结点：<br>BDHPY<br>CM<br>GQ<br>K<br>按顺序给出上述游戏中输出的叶子结点，你能输出原BST中的先序序列吗？ </p> 

 
 # 输入格式 
<p>
输入包含多组数据。每组数据包含一行或多行的大写字母。每一行描述的是上述游戏中某一轮被移除的叶子结点。同一行的字母按字母表升序排列。<br>不同组的数据间用“*”分隔。<br>最后一组数据后是一个“$”符号。<br>输入数据中没有多余的空格或空行。<br></p> 

 
 # 输出格式 
<p>
对于每组数据，都对应唯一一颗BST，你要输出该BST的先序序列（字母间不需要空格分开）。</p> 
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
<tr><td>BDHPY
CM
GQ
K
*
AC
B
$
</td><td>KGCBDHQMPY
BAC</td></tr></table>
