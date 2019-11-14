# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;王伯退休后开始养鱼。他一早起床就赶去动物园,发现这个世界的鱼真不少,五光十色、色彩斑斓,大的、小的,什么都有。这些鱼实在是太美了,买的人越来越多,湖里的鱼越来越少。没有美丽的鱼哪里有美丽的湖?于是动物园不得不规定,对于每种鱼,每个人最多可以买一条。并且有些鱼不能一起买的,因为它们之间会相互争斗吞食。<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;王伯想买尽可能多的鱼,但很可惜,他的资金有限。他冥想苦思,不知道如何是好。请编写一个程序帮助他。如果有多个方案都能买尽可能多的鱼,选择所花资金最多的一个。<br><br> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;从输入文件读入数据。输入文件的第一行为两个正整数M(M≤l000),N(≤30),分别表示&nbsp;王伯的资金和鱼的种类。以下N行,每行有两个正整数s(1≤S≤N),T,分别表示某种鱼的编号以及该鱼的价格。<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接着,每行有两个正整数P,Q。当P,Q均大于0时,表示P,Q不能共处；当P,Q均等于0时,表示输入文件的结束。<br><br><br> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件的第一行为两个正整数X,Y,分别表示所买的鱼的条数和总花费。以下X行,每行有一个正整数,表示所买的鱼的编号。编号按升序排列输出。<br>&nbsp;&nbsp;&nbsp;&nbsp;如果题目有多个解,输出其中字典序最小的一个。<br><br> 
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
<tr><td>170 7
1 70
2 50
3 30
4 40
5 40
6 30
7 20
1 4
1 7
3 4
3 5
5 7
6 7
0 0


</td><td>4 160
2
4
5
6

</td></tr></table>
