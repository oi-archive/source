# 

 
 # 题目背景 
时间：2011.4.21,自习课<BR>空间：地球<BR>人物：西部π<BR>地点：班里<BR>事件：做数学题<BR>背景：做了一个梦中梦……<BR> 

 
 # 题目描述 
在做了一个梦中梦之后，π深刻的发现了对称与平衡对解题的重要性。于是π决定研究函数以及函数图象。<BR><BR>&nbsp;<img src="/source/joyoi/tyvj-1487/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTQ4Ny8mbmJzcDtodHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL3AxNDg3LmpwZw==.jpg" border=0 align=middle><BR><BR><BR>如这个函数操所示，只要是函数都可以画出函数图象。π注意到有些函数是平衡的(专业术语叫轴对称)，还有一些函数是对称的(这里讲的是中心对称)。那么接下来的这个问题与这个有关。<BR><BR>给出一个整系数多项式函数y=f(x)，请判断该函数是平衡的还是中心对称的。(这里的对称轴仅限于平行于y轴的直线)<BR><BR> 

 
 # 输入格式 
输入数据<BR>一行，一个形如f(x)=x^2的整系数自然数指数的多项式函数(参照样例)<BR> 

 
 # 输出格式 
输出数据<BR>如果找出的是对称轴，请输出对称轴的横坐标x0(因为平行于y轴的直线都可以写成x=x0，这里所要输出的就是这个x0)；<BR>如果找出的是对称中心，请输出这个对称中心的横坐标x0，纵坐标y0，中间用一个空格隔开<BR>如果所找到的对称轴和对称中心不唯一，请输出all(因为对称轴对称中心要么只有一个，要么有很多很多个)<BR> 

 
 # 提示 
30%的数据多项式的最高次项不超过3次<BR>40%的数据各式的系数不大于1000(包括常数项)<BR>100%的数据最高次项不超过8次,多项式的各系数都不超过maxlongint，而且要么是all，要么输出的x0在-10到10之间，输出的y0的绝对值不超过maxlongint.<BR>(注意，所有的数据都为整数) 
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
<tr><td>Input1
f(x)=x^2-3^x+3^x+1


Input2
f(x)=x^2


Input3
f(x)=15x+314159</td><td>Output1
1 2

Output2
0

output3
all
</td></tr></table>
