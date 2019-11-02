# 

 
 # 题目描述 
<p>
东莞中学初中部、东城区第一中学2011年信息学第四次联考（20110409） <br>试题来源：东城一中 <br>====================================================================================================== <br><br><br><br>Density Map<br>　　问题描述<br>　　在ByteLand上有一块地区，蕴藏了ByteLand上最珍贵的Bit矿物质。科学家们将这块地区划分成了N×N个相同大小的单元格，并对每个单元格进行了考察研究：有的单元格中有丰富的Bit矿物质——科学家用1来标识；有的单元格蕴藏的矿物质很少——科学家用0来标识。<br>　　假设用W(i,j)和F(i’,j’)来分别表示两个单元格。那么它们之间的距离被定义为：max(|i - i'|, |j - j'|)，例如W(1,3)和F(4,2)的距离为3。<br>　　鉴于可持续发展的思想和开采能力的限制，ByteLand当局计划以一块单元格为中心，开采与中心距离不超过R的所有单元格内的矿藏。为了选定一个合适的单元格作中心，当局希望能够预先了解：以任意一个单元格为中心时，开采量的情况。<br>于是，当局将一张矿藏地图交给你，上面的N×N个单元格中包含数字0或1。你被要求根据这张矿藏地图，绘制出相应的“矿藏密度图”，分别以每块单元格为中心，计算与中心距离不超过R的所有标识为1的单元格个数。<br><br></p> 

 
 # 输入格式 
<p>
　　输入文件名：MAP.IN<br>　　第一行有两个数字N和R（0 <= R < N <= 250）。<br>　　以下N行，每行N个数字。第i+1行第j个数字为单元格(i,j)的标识——0或1。<br></p> 

 
 # 输出格式 
<p>
　　输出文件名：MAP.OUT<br>　　输出文件有N行，每行N个数字。第i行第j个数字表示：与(i,j)距离不超过R的所有标识为1的单元格个数。<br></p> 

 
 # 提示 
<p>
<br>====================================================================================================== <br>历史测试成绩记录，测试时间：2011年4月9日 <br>------------------------------------------------------------------------------------------------------ <br><br>杨宇通　　300　　AAAAAAAAAAAAAA	AAAAAAAAA	?????????????????????	AAAAAAAAAA	<br>伍舜豪　　240　　AAAAAAAAAAAAAA	AAAAWAWWW	AAAAAAAAAAWAWWAWWWWWW	AATATTTTTT	<br>肖遥　　　230　　AAAAAAAAAAAAAA	?????????	AWATAATATTTATTTTTTTTT	AAAAAAAAAA	<br>潘熙　　　205　　AAAAAATTATTTTT	AAAAAAAAA	AAAAAAAAAWWAWWAWWWWWW	AWWWWWWWWW	<br>冯灏帆　　190　　AAAAAAAAAAAAAA	AAWAWWBBB	AAAAWAAAAAAAWWAWWWWWW	WWWWWWWWWW	<br>袁嘉豪　　185　　AAAAAAAAAAAAAA	AAAAAAAAT	?????????????????????	??????????	<br>谢玮鸿　　180　　AAAAAATTATTTTT	AAAAAAAAA	AAAWAAAAWWWAWWWWWWWWW	??????????	<br>麦辉煜　　180　　AAAAAATTATTTTT	AAAAWAWWA	AAAAAAAAAAAAAAAWWWWWW	??????????	<br>王誉锋　　165　　AAAAAATTATTTTT	AAAAAAAAW	AAAWAAAAWWWAWWWWWWWWW	----------	<br>钟嘉声　　135　　AAAAAATTATTTTT	AAAAAAABB	AAAWWWWWWWWWWWWWWWWWW	AWWWWWWWWW	<br>孔智谦　　110　　AAAAAATTATTTTT	AAAAWAWWW	AAAWAWWWWWWWWWWWWWWWW	??????????	<br>张嘉曦　　100　　--------------	AAAAAAAAA	?????????????????????	??????????	<br>林雪晴　　90　　　AAWWWWWWWWWWWW	AAAAAATTT	MMMMMMMMMMMMMMMMMMMMM	WAAWWWWWWW	<br>======================================================================================================</p> 
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
<tr><td>5 1
1 0 0 0 1
1 1 1 0 0 
1 0 0 0 0 
0 0 0 1 1
0 1 0 0 0
</td><td>3 4 2 2 1
4 5 2 2 1
3 4 3 3 2
2 2 2 2 2
1 1 2 2 2
</td></tr></table>
