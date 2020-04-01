# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;斜堆(skew&nbsp;heap)是一种常用的数据结构。它也是二叉树，且满足与二叉堆相<BR>同的堆性质：&nbsp;每个非根结点的值都比它父亲大。&nbsp;因此在整棵斜堆中，&nbsp;根的值最小。<BR>但斜堆不必是平衡的，每个结点的左右儿子的大小关系也没有任何规定。在本题<BR>中，斜堆中各个元素的值均不相同。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;在斜堆&nbsp;H&nbsp;中插入新元素&nbsp;X&nbsp;的过程是递归进行的：当&nbsp;H&nbsp;为空或者&nbsp;X&nbsp;小于&nbsp;H<BR>的根结点时&nbsp;X&nbsp;变为新的树根，而原来的树根（如果有的话）变为&nbsp;X&nbsp;的左儿子。<BR>当&nbsp;X&nbsp;大于&nbsp;H&nbsp;的根结点时，H&nbsp;根结点的两棵子树交换，而&nbsp;X（递归）插入到交换<BR>后的左子树中。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;给出一棵斜堆，包含值为0~n的结点各一次。求一个结点序列，使得该斜堆<BR>可以通过在空树中依次插入这些结点得到。如果答案不惟一，输出字典序最小的<BR>解。输入保证有解。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;第一行包含一个整数n。第二行包含n个整数d1,&nbsp;&nbsp;d2,&nbsp;&nbsp;...&nbsp;&nbsp;,&nbsp;&nbsp;dn，&nbsp;di&lt;100表示i<BR>是&nbsp;di的左儿子，di&gt;=100&nbsp;表示&nbsp;i&nbsp;是&nbsp;di-100&nbsp;的右儿子。显然&nbsp;0&nbsp;总是根，所以输入中<BR>不含d0。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;仅一行，包含n+1整数，即字典序最小的插入序列。 

 
 # 提示 
2&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;50SCOI2008&nbsp;day1&nbsp;T3 
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
<tr><td>样例1：

6 
100 0 101 102 1 2  

样例2：

6 
100 0 2 102 4 104

样例3：

7 
0 100 1 102 2 3 5</td><td>样例1：

0 1 2 3 4 5 6 

样例2：

4 6 5 2 0 1 3 

样例3：

2 5 0 3 4 6 7 1 </td></tr></table>
