# 

 
 # 题目背景 
深绘里一直很讨厌雨天。<BR>灼热的天气穿透了前半个夏天，后来一场大雨和随之而来的洪水，浇灭了一切。<BR>虽然深绘里家乡的小村落对洪水有着顽固的抵抗力，但也倒了几座老房子，几棵老树被连根拔起，以及田地里的粮食被弄得一片狼藉。<BR>无奈的深绘里和村民们只好等待救济粮来维生。<BR>不过救济粮的发放方式很特别。 

 
 # 题目描述 
首先村落里的一共有n座房屋，并形成一个树状结构。然后救济粮分m次发放，每次选择两个房屋(x,y)，然后对于x到y的路径上（含x和y)每座房子里发放一袋z类型的救济粮。<BR>然后深绘里想知道，当所有的救济粮发放完毕后，每座房子里存放的最多的是哪种救济粮。<BR> 

 
 # 输入格式 
第一行两个正整数n,m，含义如题目所示。<BR>接下来n-1行，每行两个数(a,b)，表示(a,b)间有一条边。<BR>再接下来m行，每行三个数(x,y,z)，含义如题目所示。<BR> 

 
 # 输出格式 
n行，第i行一个整数，表示第i座房屋里存放的最多的是哪种救济粮，如果有多种救济粮存放次数一样，输出编号最小的。<BR>如果某座房屋里没有救济粮，则对应一行输出0。<BR> 

 
 # 提示 
对于20%的数据，1&nbsp;&lt;=&nbsp;n,&nbsp;m&nbsp;&lt;=&nbsp;100<BR>对于50%的数据，1&nbsp;&lt;=&nbsp;n,&nbsp;m&nbsp;&lt;=&nbsp;2000<BR>对于100%的数据，1&nbsp;&lt;=&nbsp;n,&nbsp;m&nbsp;&lt;=&nbsp;100000,&nbsp;1&nbsp;&lt;=&nbsp;a,&nbsp;b,&nbsp;x,&nbsp;y&nbsp;&lt;=&nbsp;n,&nbsp;1&nbsp;&lt;=&nbsp;z&nbsp;&lt;=&nbsp;100000<BR>Vani 
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
<tr><td>5 3
1 2
3 1
3 4
5 3
2 3 3
1 5 2
3 3 3
</td><td>2
3
3
0
2
</td></tr></table>
