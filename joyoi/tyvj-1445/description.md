# 

 
 # 题目背景 
非原创 

 
 # 题目描述 
在完成了古越州圆盘密码的研究之后，考古学家小布来到了南美大陆的西部。相传很久以前这片土地上生活着两个部落，一个部落崇拜闪电，一个部落崇拜高山，他们分别用闪电和高山的形状来作为各自部落的图腾。<BR>小布的团队在山洞里发现了一幅巨大的壁画，壁画上被标记出了N个点，经测量发现这N个点的水平位置和竖直位置是两两不同的。小布认为这幅壁画所包含的信息与这N个点的相对位置有关，因此不妨设坐标分别为(1,y1),(2,y2),…,(n,yn),其中y1~yn是1到n的一个排列。<BR>小布的团队打算研究这幅壁画中包含着多少个图腾，其中闪电图腾的定义如图所示如下（注意：图腾的形式只和这4个纵坐标的大小排列顺序有关）：<BR>&nbsp;<img src="/source/joyoi/tyvj-1445/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTQ0NS8mbmJzcDtodHRwOi8vdHl2ai5jcHd6LmNuL3Byb2JsZW1pbWcvcDE0NDUtMi5qcGc=.jpg" border=0 align=middle><BR>即1&lt;=a&lt;b&lt;c&lt;d&lt;=N,ya&lt;yc&lt;yb&lt;yd<BR>崇拜高山的部落有两个氏族，因而山峰图腾有如下两种形式，左图为A类，右图为B类(同样，图腾的形式也只与4个纵坐标的大小排列顺序有关)：<BR>&nbsp;<img src="/source/joyoi/tyvj-1445/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTQ0NS8mbmJzcDtodHRwOi8vdHl2ai5jcHd6LmNuL3Byb2JsZW1pbWcvcDE0NDUtMS5qcGc=.jpg" border=0 align=middle><BR>&nbsp;<img src="/source/joyoi/tyvj-1445/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTQ0NS8mbmJzcDtodHRwOi8vdHl2ai5jcHd6LmNuL3Byb2JsZW1pbWcvcDE0NDUtMy5qcGc=.jpg" border=0 align=middle><BR>即1&lt;=a&lt;b&lt;c&lt;d&lt;=N,ya&lt;yb&lt;yd&lt;yc或者ya&lt;yd&lt;yc&lt;yb<BR>小步的团队希望知道，这n个点中两个部落图腾数目的差值。因此，你需要编写一个程序来计算闪电图腾数目减去山峰数目的值，由于这个值的绝对值可能比较大，本题目中只需要输出该值对16777216的余数(注意余数必为正值，例如-1对16777216的余数为16777215)<BR> 

 
 # 输入格式 
第一行包含一个整数N，为点的数目。<BR>接下来一行包含N个整数，分别为y1，y2，…，yn。保证这n个数是1~N的一个排列。<BR> 

 
 # 输出格式 
包含一个数，表示闪电图腾数目与山峰图腾数目的差值对16777216的余数。 

 
 # 提示 
数据范围约定<BR>10%的数据&nbsp;n&lt;=600<BR>40%的数据&nbsp;n&lt;=5000<BR>100%的数据&nbsp;n&lt;=200000 
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
<tr><td>5
1 5 3 2 4

</td><td>0
</td></tr></table>
