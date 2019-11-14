# 

 
 # 题目背景 
抗战系列 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;ForeverBell不仅精通破译密码,更是我军的重要代码编写者(至于什么代码,自己想吧).战争的日子是无聊的,有一天,ForeverBell找到了treeboy,出了一个极其简单的问题:给定一段序列,找出这段数列中第k小的数.<BR>&nbsp;&nbsp;&nbsp;&nbsp;为了照顾treeboy的超弱语文水平,ForeverBell极其耐心地解释了这个问题:给定一个整数数列num[1...n],序列中的每个数字都不相同.你需要回答一组格式为Q(i,j,k)的查询,表示"在num[i...j]中第k小的数是多少".<BR>&nbsp;&nbsp;&nbsp;&nbsp;由于treeboy不仅语文差,而且代码能力巨弱,所以再次找到了你,请你编写一个程序,应对ForeverBell的询问.<BR> 

 
 # 输入格式 
第一行两个整数n,m.分别是数列的总长度和ForeverBell询问的次数.&nbsp;1≤n≤100&nbsp;000，1≤m≤5&nbsp;000<BR>第二行有n个数，代表数列的元素，所有数都不相同，而且不会超过10^9&nbsp;。<BR>接下来有m行，每行三个整数i、j、k，代表一次查询，i、j、k满足：1≤i≤j≤n，&nbsp;1≤k≤j-i+1。&nbsp; 

 
 # 输出格式 
一共m行.第i行表示第i次询问的答案. 

 
 # 提示 
样例解释:<BR>数列num[2..5]中第3小的数是5<BR>数列num[4..4]中第1小的数是1<BR>数列num[1..7]中第3小的数是3<BR>经典问题改编 
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
<tr><td>7 3
1 5 2 6 3 7 4
2 5 3
4 4 1
1 7 3</td><td>5
6
3
</td></tr></table>
