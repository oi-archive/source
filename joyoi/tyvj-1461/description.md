# 

 
 # 题目描述 
Byteland总统Bob对Treeland进行访问。会谈之后，Bob希望对Treeland尽可能多的城市进行考察。但是，显然Treeland民众不希望Bob前来考察(又要封道什么的)，所以Treeland决定Bob所考察的任意两座城市之间的距离不小于L。Treeland由N座城市组成，任意两个城市之间有且仅有一条简单路径，也就是说N个城市构成一棵树。 

 
 # 输入格式 
第一行两个整数，N和L，含义如题目所述；<BR>以下N-1行，每行三个整数，Ai,&nbsp;Bi,&nbsp;Di，表示编号为Ai和Bi的城市之间有一条路，长度为Di。<BR>输入保证是一棵树。 

 
 # 输出格式 
仅一行，一个整数，表示最多可考察的城市数目。 

 
 # 提示 
<B>数据规模及约定</B><BR>对于10%的数据，N&nbsp;&lt;=&nbsp;20，L&nbsp;&lt;=&nbsp;2000;<BR>另有10%的数据，N&nbsp;&lt;=&nbsp;5000,&nbsp;Di&nbsp;=&nbsp;1;<BR>对于30%的数据，N&nbsp;&lt;=&nbsp;5000;<BR>另有20%的数据，N&nbsp;&lt;=&nbsp;10^5，且树的生成方法是随机地生成一个序列，然后对每个点随机地指定一个在其之前的点与其直接相连;<BR>对于70%的数据，N&nbsp;&lt;=&nbsp;10^5;<BR>对于100%的数据，N&nbsp;&lt;=&nbsp;5×10^5;<BR>对于100%的数据，任意两点间的距离不超过10^9。<BR><BR><B>提示</B><BR>本题I/O量较大，建议C++选手使用scanf进行读入；<BR>栈空间限制为2M。<BR>奇异夸克<BR>2011MarchTYVJ月赛(省选难度)<BR> 
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
<tr><td>5 2
1 2 1
1 3 1
1 4 1
4 5 1
</td><td>3
</td></tr></table>
