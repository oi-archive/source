# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;张老师根据自己工作的需要，设计了一种特殊的二叉搜索树。他把这种二叉树起名为zh_tree，对于具有n个结点的zh_tree，其中序遍历恰好为(1，2，3，…，n)，其中数字1，2，3，…，n&nbsp;是每个结点的编号。n个结点恰好对应于一组学术论文中出现的n个不同的单词。第j个单词在该组论文中出现的次数记为dj，例如，d2=10表示第2个结点所对应的单词在该组论文中出现了10次。设该组论文中出现的单词总数为S，显然，S=d1+d2+…+dn。记fj=dj/S为第j个单词在该组论文中出现的概率（频率）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;张老师把根结点深度规定为0，根结点子女的深度规定为1，依次类推。如果第j个结点的深度为r，则访问该结点的代价hj为hj=k(r+1)+c，其中k，c为已知的不超过100的正常数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;则zh_tree是满足以下条件的一棵二叉树：它使h1f1+h2f2+…+hnfn<BR>达到最小。我们称上式为访问zh_tree的平均代价。<BR>&nbsp;&nbsp;&nbsp;&nbsp;请你根据已知数据为张老师设计一棵zh_tree。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第1行：3个用空格隔开的正数：<BR>n&nbsp;k&nbsp;c<BR>其中n&lt;50，为整数，k，c为不超过100的正实数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2行：n个用空格隔开的正整数，为每个单词出现的次数(次数&lt;200)。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出一个正实数，保留3位小数，为访问Zh_tree的最小平均代价。 

 
 # 提示 
SCOI2006&nbsp;T1 
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
<tr><td>4  2  3.5
20  30  50  20

</td><td>7.000
（每行以数字开始，不要有多余的空格）
</td></tr></table>
