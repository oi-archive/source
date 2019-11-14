# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;fox来到了一排葡萄架下,葡萄架上有很多葡萄(n串),它想将一部分葡萄偷走.<BR>&nbsp;&nbsp;&nbsp;&nbsp;每串葡萄都有一个价值,当然,由于有酸有甜,葡萄的价值可能为正,也可能为负.<BR>&nbsp;&nbsp;&nbsp;&nbsp;当然,为了让农夫看不出来,fox规定,每k串葡萄中,它最多选b串,但是由于fox是比较贪心的,每连续k串葡萄中,它会最少选a串<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如n=5&nbsp;k=3&nbsp;a=1&nbsp;b=2时,在第1--第3串葡萄中,fox只能选1或2串,在第2--第4串葡萄中,fox也只能选1或2串.<BR>&nbsp;&nbsp;&nbsp;&nbsp;图1的选法是不合法的,因为2--4中选出了3串葡萄<BR>&nbsp;&nbsp;&nbsp;&nbsp;图2的选法也是不合法的,因为1--3中选出了0串葡萄<BR>&nbsp;&nbsp;&nbsp;&nbsp;而图3的选法是合法的.<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在,fox要选出一些葡萄,而农夫得到剩余的葡萄,由于fox有嫉妒心理,希望让fox得到的价值减去农夫得到的价值的差值最大<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行整数n,k,a,b<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行n个整数表示每串葡萄的价值 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;仅一行,表示答案 

 
 # 提示 
对于10%的数据&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&lt;=10<BR>对于另外30%的数据&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a=0,b=k<BR>对于100%数据	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&lt;=10000,0&lt;=a&lt;=b&lt;=k&lt;=10来源：fox_pro&nbsp;&nbsp;&nbsp;&nbsp;开学欢乐赛 
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
<tr><td>2 1 0 1
2 -2</td><td>4
</td></tr></table>
