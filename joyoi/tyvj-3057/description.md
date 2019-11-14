# 

 
 # 题目描述 
<p>
树在计算机领域的应用相当广泛。或许用得最多的就是有根二叉树。但也有其他的有根树非常实用，比如有序树，即任意结点的所有子树都是有序的。每个结点的孩子数不是固定的。形式化描述，一棵有序树的结点包含在有限集合T中：<br>有一个根结点，表示为root(T)；<br>剩下的结点被划分为集合T1，T2，…,Tm，每个集合也是一棵树（子树）。<br>类似地定义root(T1)，…，root(Tm)为root(T)的孩子，其中root(Ti)是第i个孩子。结点root(T1)，…，root(Tm)是兄弟结点。<br>如果把有序数表示为有根二叉树，所有结点都能用同样大小的内存空间存储，实现起来更方便。转换步骤如下：<br>1. 删除有序数中的所有边；<br>2. 对于每个结点，添加一条到其第一个孩子的边，将第一个孩子作为该结点的左孩子；<br>3. 对于每个结点，添加一条到其下一个兄弟的边，将下一个兄弟作为该结点的右孩子。<br>例如：<br><img src="/source/joyoi/tyvj-3057/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA1Ny9wcm9ibGVtc19pbWFnZXMvMzY4Ni8xLmpwZw==.jpg"></img><br><br><br>有些情况下，这样子的转换会导致树高（从根到叶子的最长距离）增加。这不是我们所期望的，因为很多算法的复杂度取决于树高。<br>你的任务是写一个程序，计算转换前后的树高分别为多少。<br></p> 

 
 # 输入格式 
<p>
输入包含许多行，每一行给出深度优先搜索过程中的方向。每棵树一行。<br>比如，上述的树可以表示为dudduduudu，意味着0向下到1,1向上到0,0向下到2，以此类推。输入以首字符为#的一行结束。你可以假设每棵树至少有2个至多不超过10000个结点。<br></p> 

 
 # 输出格式 
<p>
对于每棵树，输出转换前后该数的高度。转换方法如题意所述。<br>输出使用如下格式：<br>Tree t: h1 => h2<br>其中t是树的编号（从1开始），h1是转换前的树高，h2是转换为二叉树后的树高。.<br></p> 
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
Tree 4: 4 => 4</td></tr></table>
