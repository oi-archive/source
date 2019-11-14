# 

 
 # 题目描述 
Blackbox是一种原始的数据库。它可以储存一个整数数组，还有一个特别的变量i，最开始的时候blackbox是空的，而i等于0。这个blackbox要处理一串命令。<BR>命令只有两种：<BR>Add(x)：把x元素放进blackbox；<BR>Get：i加1，然后输出blackbox中第i小的数。<BR>记住：第i小的数，就是blackbox里的数的按从小到大的顺序排序后的第i个元素。<BR>例如：<BR>&nbsp;&nbsp;我们来演示一下一个有11个命令的命令串。<BR>序号	操作	&nbsp;&nbsp;&nbsp;&nbsp;i	&nbsp;&nbsp;数据库	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输出<BR>1	Add(3)	&nbsp;&nbsp;&nbsp;&nbsp;0	&nbsp;&nbsp;&nbsp;&nbsp;3	<BR>2	Get	&nbsp;&nbsp;&nbsp;&nbsp;1	&nbsp;&nbsp;&nbsp;&nbsp;3	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3<BR>3	Add(1)	&nbsp;&nbsp;&nbsp;&nbsp;1	&nbsp;&nbsp;&nbsp;&nbsp;1,3	<BR>4	Get	&nbsp;&nbsp;&nbsp;&nbsp;2	&nbsp;&nbsp;&nbsp;&nbsp;1,3	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3<BR>5	Add(-4)	&nbsp;&nbsp;&nbsp;&nbsp;2	&nbsp;&nbsp;&nbsp;&nbsp;-4,1,3	<BR>6	Add(2)	&nbsp;&nbsp;&nbsp;&nbsp;2	&nbsp;&nbsp;&nbsp;&nbsp;-4,1,2,3	<BR>7	Add(8)	&nbsp;&nbsp;&nbsp;&nbsp;2	&nbsp;&nbsp;&nbsp;&nbsp;-4,1,2,3,8	<BR>8	Add(-1000)&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-1000,-4,1,2,3,8	<BR>9	Get	&nbsp;&nbsp;&nbsp;&nbsp;3	&nbsp;&nbsp;&nbsp;&nbsp;-1000,-4,1,2,3,8	1<BR>10	Get	&nbsp;&nbsp;&nbsp;&nbsp;4	&nbsp;&nbsp;&nbsp;&nbsp;-1000,-4,1,2,3,8	2<BR>11	Add(2)	&nbsp;&nbsp;&nbsp;&nbsp;4	&nbsp;&nbsp;&nbsp;&nbsp;-1000,-4,1,2,2,3,8	<BR><BR>现在要求找出对于给定的命令串的最好的处理方法。Add和get命令分别最多有200000个。<BR>现在用两个整数数组来表示命令串：<BR>1，A(1)，A(2)……A(m)：一串将要被放进black&nbsp;box的元素。每个数据都是绝对值不超过2000000000的整数，m≤200000。例如上面的例子就是A=（3，1，-4，2，8，-1000，2）。<BR>2、u(1)，u(2)……u(n)：表示第u&nbsp;(j)个元素被放进了black&nbsp;box&nbsp;里后出现一个get命令。例如上面的例子中u=(1,2,6,6)。输入数据不用判错。<BR> 

 
 # 输入格式 
第1行：两个整数M，N。<BR>第2行：M个整数，表示A(1)……A(m)<BR>第3行：N个整数，表示u(1)……u&nbsp;(n)<BR> 

 
 # 输出格式 
输出black&nbsp;box根据命令串所得出的输出串，一个数字一行。 

 
 # 提示 
By:space7 
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
<tr><td>7 4
3 1 -4 2 8 -1000 2
1 2 6 6 
</td><td>3
3
1
2
</td></tr></table>
