# 
众所周知，小F是实验室最弱的人，经常被大家欺负，某天，大贤者wwy又一次准备欺负小F了，现在已经知道小F在某个长为m的直线上，直线上第i个点的高度为ai，他准备将小F打飞，当小F飞到比小F原来所在点的地方更高的1地方时，小F就会停止飞行嵌在墙上，出于人道主义，WWY想让小F飞的远一些。他想知道小F在b点时会飞多远，如果左边远则输出"L"，如果右边远则输出"R"，如果左边和右边相同则输出"S"，为了不让小F飞太远，他将线段的0点和m+1点设置为无限大。
输入
第一行两个整数，线段长度m，查询次数n（1<=M,N<=100000)
第二行m个整数，线段第i个点长度ai(1<ai<1e9)
第三行到第2+n行，wwy的询问b（1<=b<=m)
输出
n行，根据询问回答"S","R","L"
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
5 1 2 3 5
1
2</td><td>L
S
</td></tr></table>
