# 

 
 # 题目描述 
<p>
吃西瓜（matrix.pas\c\cpp）<br><br>【说明】<br>　　此题中出现的所有数全为整数<br><br>【题目背景】<br>　　SubRaY有一天得到一块西瓜,是长方体形的....<br><br>【题目描述】<br>　　SubRaY发现这块西瓜长m厘米,宽n厘米,高h厘米.他发现如果把这块西瓜平均地分成m*n*h块1立方厘米的小正方体,那么每一小块都会有一个营养值(可能为负,因为西瓜是有可能坏掉的,但是绝对值不超过200).<br>　　现在SubRaY决定从这m*n*h立方厘米的西瓜中切出mm*nn*hh立方厘米的一块小西瓜(一定是立方体形,长宽高均为整数),然后吃掉它.他想知道他最多能获得多少营养值.(0<=mm<=m,0<=nn<=n,0<=hh<=h.mm,nn,hh的值由您来决定).<br>　　换句话说,我们希望从一个m*n*h的三维矩阵中,找出一个三维子矩阵,这个子矩阵的权和最大.<br><br><center><img src="/source/joyoi/tyvj-3432/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQzMi9wcm9ibGVtc19pbWFnZXMvMjIzMC8xLmpwZw==.jpg"></img></center><br><br><center>一个2*3*4的例子,最优方案为切红色2*3*1部分</center></p> 

 
 # 输入格式 
<p>
　　输入文件matrix.in首行三个数h,m,n(注意顺序),分别表示西瓜的高,长,宽.<br>　　以下h部分,每部分是一个m*n的矩阵,第i部分第j行的第k个数表示西瓜第i层,第j行第k列的那块1立方厘米的小正方体的营养值.<br></p> 

 
 # 输出格式 
<p>
　　输出文件matrix.out输出SubRaY所能得到的最大营养值<br></p> 

 
 # 提示 
<p>
【数据范围】<br>　　对于30%的数据,h=1,1<=m,n<=10<br>　　对于全部的数据,1<=h<=32,1<=m,n<=50,保证h<=m,n<br></p> 
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
<tr><td>2 3 4
4 1 2 8
0 5 -48 4
3 0 1 9
2 1 4 9
1 0 1 7
3 1 2 8
</td><td>
45</td></tr></table>
