# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;几乎整个Byteland&nbsp;王国都被森林和河流所覆盖。小点的河汇聚到一起，形成了稍大点的河。就这样，所有的河水都汇聚并流进了一条大河，最后这条大河流进了大海。这条大河的入海口处有一个村庄——Bytetown。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在Byteland国，有n个伐木的村庄，这些村庄都座落在河边。目前在Bytetown，有一个巨大的伐木场，它处理着全国砍下的所有木料。木料被砍下后，顺着河流而被运到Bytetown的伐木场。Byteland&nbsp;的国王决定，为了减少运输木料的费用，再额外地建造k个伐木场。这k个伐木场将被建在其他村庄里。这些伐木场建造后，木料就不用都被送到Bytetown了，它们可以在&nbsp;运输过程中第一个碰到的新伐木场被处理。显然，如果伐木场座落的那个村子就不用再付运送木料的费用了。它们可以直接被本村的伐木场处理。<BR>注：所有的河流都不会分叉，形成一棵树，根结点是Bytetown。<BR>&nbsp;&nbsp;&nbsp;&nbsp;国王的大臣计算出了每个村子每年要产多少木料，你的任务是决定在哪些村子建设伐木场能获得最小的运费。其中运费的计算方法为：每一吨木料每千米1分钱。<BR>&nbsp;&nbsp;&nbsp;&nbsp;编一个程序：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;1．从文件读入村子的个数，另外要建设的伐木场的数目，每年每个村子产的木料的块数以及河流的描述。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;2．计算最小的运费并输出。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行包括两个数n（2&lt;=n&lt;=100），k（1&lt;=k&lt;=50,且k&lt;=n）。n为村庄数，k为要建的伐木场的数目。除了Bytetown&nbsp;外，每个村子依次被命名为&nbsp;1，2，3……n，Bytetown被命名为0。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，每行3个整数：<BR>&nbsp;&nbsp;&nbsp;&nbsp;wi——每年&nbsp;i&nbsp;村子产的木料的块数。（0&lt;=wi&lt;=10000）&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;vi——离&nbsp;i&nbsp;村子下游最近的村子。（即&nbsp;i&nbsp;村子的父结点）（0&lt;=vi&lt;=n）&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;di——vi&nbsp;到&nbsp;i&nbsp;的距离(千米)。（1&lt;=di&lt;=10000）&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;保证每年所有的木料流到bytetown&nbsp;的运费不超过2000,000,000分&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;50％的数据中n不超过20。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出最小花费，精确到分。 

 
 # 提示 
树形动态规划<BR><BR>经典问题 
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
<tr><td>4 2 
1 0 1 
1 1 10 
10 2 5 
1 2 3 </td><td>4</td></tr></table>
