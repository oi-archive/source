# 

 
 # 题目描述 
<p>
树在计算机领域的应用相当广泛。或许用得最多的就是有根二叉树。但也有其他的有根树非常实用，比如有序树，即任意结点的所有子树都是有序的。每个结点的孩子数不是固定的。形式化描述，一棵有序树的结点包含在有限集合T中：

 
 # 输入格式 
<p>
输入包含许多行，每一行给出深度优先搜索过程中的方向。每棵树一行。

 
 # 输出格式 
<p>
对于每棵树，输出转换前后该数的高度。转换方法如题意所述。
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
<tr><td>dudduduudu
ddddduuuuu
dddduduuuu
dddduuduuu
#
</td><td>Tree 1: 2 => 4
Tree 2: 5 => 5
Tree 3: 4 => 5
Tree 4: 4 => 4