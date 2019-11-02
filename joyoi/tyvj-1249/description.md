# 

 
 # 题目描述 
给出一有向图，图中每条边都被标上了关系运算符‘&lt;’,‘&gt;’,‘=’。现在要给图中每个顶点标上一个大于等于0,小于等于k的某个整数使所有边上的符号得到满足。若存在这样的k，则求最小的k，若任何k都无法满足则输出NO。<BR><BR>例如下表中最小的k为2。<BR><BR>结点1&gt;结点2<BR>结点2&gt;结点3<BR>结点2&gt;结点4<BR>结点3=结点4<BR><BR>如果存在这样的k，输出最小的k值；否则输出‘NO’。<BR><BR> 

 
 # 输入格式 
共二行，第一行有二个空格隔开的整数n和m。n表示G的结点个数，m表示G的边数，其中1&lt;=n&lt;=1000,&nbsp;0&lt;=m&lt;=10000。全部结点用1到n标出，图中任何二点之间最多只有一条边，且不存在自环。<BR>第二行共有3m个用空格隔开的整数，第3i-2和第3i-1（1&lt;=i&lt;=m）个数表示第i条边的顶点。第3i个数表示第i条边上的符号，其值用集合{-1，0，1}中的数表示：-1表示‘&lt;’,&nbsp;0&nbsp;表示‘=’,&nbsp;1表示‘&gt;’。<BR> 

 
 # 输出格式 
仅一行，如无解则输出‘NO’；否则输出最小的k的值。<BR> 
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
<tr><td>4 4
1 2 -1 2 3 0 2 4 -1 3 4 -1
</td><td>2
</td></tr></table>
