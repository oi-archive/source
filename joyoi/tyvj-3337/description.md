# 

 
 # 题目描述 
<p>
离散函数的斜率（Function.pas\c\cpp）<br><br>【题目描述】<br>　　函数的斜率总是有着各种各样特殊的意义，其极值也是人们研究的重点，现在你将要解决下面的问题：<br>　　给出一个离散函数，这个离散函数是由{1,2,3,4......N}到[-2^31,2^31]的一个映射,现在你要在这个函数上找两个不同的点,使得函数在两点之间的点都在这两点连线的下方(严格小于),并且使得过这两点的直线的斜率尽可能的大.<br><br><center><img src="/source/joyoi/tyvj-3337/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMzNy9wcm9ibGVtc19pbWFnZXMvMjExMS8xLmpwZw==.jpg"></img></center><br></p> 

 
 # 输入格式 
<p>
　　输入文件function.in的第一行一个N,表示这个离散函数有N个点.(1<=N<=100000)<br>　　下面N行,每行一个整数,第I行表示第I个点（即横坐标为I）的函数值.<br></p> 

 
 # 输出格式 
<p>
　　输出文件为function.out<br>　　如果找不到解,则输出-1,否则第一行输出一个实数,表示最大的斜率,保留6位小数.第二行两个数,有一个空格隔开,表示这两个点的横坐标(即是第几个点),必须保证第一个数小于第二个数.如果有多组解,则输出两个点横坐标相隔最远的一组,如果还有多个,则输出第一个点最靠后的.</p> 

 
 # 提示 
<p>
【数据规模】	<br>　　对于20%的数据,有N<=100	<br>　　对于40%的数据,有N<=3000<br>　　对于100%的数据有N<=100000.<br><br>【提示】	<br>　　如果两个数a,b,有a-b的绝对值小于等于1E-10,可以看作a=b.<br></p> 
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
<tr><td>3
2
3
2</td><td>1.000000
1 2</td></tr></table>
