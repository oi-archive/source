# 

 
 # 题目背景 
NOIP2011&nbsp;day1&nbsp;第一题<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;为了准备一个独特的颁奖典礼，组织者在会场的一片矩形区域（可看做是平面直角坐标系的第一象限）铺上一些矩形地毯。一共有&nbsp;n&nbsp;张地毯，编号从&nbsp;1&nbsp;到n&nbsp;。现在将这些地毯按照编号从小到大的顺序平行于坐标轴先后铺设，后铺的地毯覆盖在前面已经铺好的地毯之上。地毯铺设完成后，组织者想知道覆盖地面某个点的最上面的那张地毯的编号。注意在矩形地毯边界和四个顶点上的点也算被地毯覆盖。 

 
 # 输入格式 
第一行，一个整数n&nbsp;，表示总共有&nbsp;n&nbsp;张地毯。&nbsp;<BR>接下来的n&nbsp;行中，第&nbsp;i+1&nbsp;行表示编号i&nbsp;的地毯的信息，包含四个正整数&nbsp;a&nbsp;，b&nbsp;，g&nbsp;，k&nbsp;，每两个整数之间用一个空格隔开，分别表示铺设地毯的左下角的坐标（a&nbsp;，b&nbsp;）以及地毯在x轴和y&nbsp;轴方向的长度。&nbsp;<BR>第n+2&nbsp;行包含两个正整数&nbsp;x&nbsp;和y，表示所求的地面的点的坐标（x&nbsp;，y）。&nbsp; 

 
 # 输出格式 
输出共1&nbsp;行，一个整数，表示所求的地毯的编号；若此处没有被地毯覆盖则输出-1&nbsp;。 

 
 # 提示 
对于30%&nbsp;的数据，有&nbsp;n&nbsp;≤2&nbsp;；&nbsp;<BR>对于50%&nbsp;的数据，0&nbsp;≤a,&nbsp;b,&nbsp;g,&nbsp;k≤100；&nbsp;<BR>对于100%的数据，有&nbsp;0&nbsp;≤n&nbsp;≤10,000&nbsp;，0≤a,&nbsp;b,&nbsp;g,&nbsp;k&nbsp;≤100,000。&nbsp; 
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
<tr><td>input1
3 
1 0 2 3
0 2 3 3
2 1 3 3
2 2 

input2
3 
1 0 2 3 
0 2 3 3 
2 1 3 3   
4 5
</td><td>output1
3

output2
-1

对输出1的说明

如下图(图暂缺)，1 号地毯用实线表示，2 号地毯用虚线表示，3 号用双实线表示，覆盖点（2 ，
2 ）的最上面一张地毯是 3 号地毯。 

对输出2的说明
如上图（图暂缺），1 号地毯用实线表示，2 号地毯用虚线表示，3 号用双实线表示，点（4，5 ）
没有被地毯覆盖，所以输出-1。 </td></tr></table>
