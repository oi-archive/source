# 

 
 # 题目背景 
NOIP2008第四题加强版<BR> 

 
 # 题目描述 
Tom最近在研究一个有趣的排序问题。如图所示，通过2个栈S1和S2，Tom希望借助以下4种操作实现将输入序列升序排序。<BR><BR><img src="/source/joyoi/tyvj-1535/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUzNS9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzExMjEtMS5naWY=.gif" border=0 align=middle><BR><BR>操作a<BR>如果输入序列不为空，将第一个元素压入栈S1<BR>操作b<BR>如果栈S1不为空，将S1栈顶元素弹出至输出序列<BR>操作c<BR>如果输入序列不为空，将第一个元素压入栈S2<BR>操作d<BR>如果栈S2不为空，将S2栈顶元素弹出至输出序列<BR><BR><img src="/source/joyoi/tyvj-1535/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUzNS9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzExMjEtMi5naWY=.gif" border=0 align=middle><BR><BR>如果一个1~n的排列P可以通过一系列操作使得输出序列为1,&nbsp;2,…,(n-1),&nbsp;n，Tom就称P是一个"可双栈排序排列"。例如(1,&nbsp;3,&nbsp;2,&nbsp;4)就是一个"可双栈排序序列"，而(2,&nbsp;3,&nbsp;4,&nbsp;1)不是。下图描述了一个将(1,&nbsp;3,&nbsp;2,&nbsp;4)排序的操作序列：&lt;a,&nbsp;c,&nbsp;c,&nbsp;b,&nbsp;a,&nbsp;d,&nbsp;d,&nbsp;b&gt;<BR><BR><BR>当然，这样的操作序列有可能有几个，对于上例(1,&nbsp;3,&nbsp;2,&nbsp;4)，&lt;a,&nbsp;c,&nbsp;c,&nbsp;b,&nbsp;a,&nbsp;d,&nbsp;d,&nbsp;b&gt;是另外一个可行的操作序列。Tom希望知道其中字典序最小的操作序列是什么。<BR><BR> 

 
 # 输入格式 
输入的第一行是一个整数p，有p组测试数据，每组测试数据的第一行有一个正整数n，第二行有n个用空格隔开的正整数，构成一个1~n的排列。<BR> 

 
 # 输出格式 
输出共p行，如果输入的排列不是"可双栈排序排列"，输出数字0；否则输出字典序最小<BR>的操作序列，每两个操作之间用空格隔开，行尾没有空格。<BR> 

 
 # 提示 
100%的数据满足：&nbsp;n&lt;=10^5<BR> 
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
<tr><td>1
3
2 3 1

</td><td>a c a b b d</td></tr></table>
