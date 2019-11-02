# 

 
 # 题目描述 
<p>
背景：<br>　　忙碌的chnlkw还要参加今年的noip，所以不能花太多的时间举办生日party。他请你计算生日这一天里能干多少事。<br><br>问题描述：<br>　　Chnlkw将一天划分为n个单位时间，他告诉了你这天可以干的m件事情，每件事情i从第Si个单位时间开始，第Ei个单位时间结束，完成这件事情能有Pi的价值。Chnlkw希望在每一个单位时间内都专心致志地做一件事情，并且每一件事都自始至终地完成。（chnlkw：555本来想偷懒的）<br><br></p> 

 
 # 输入格式 
<p>
　　第一行为一个整数n。<br>　　第二行为一个整数m。<br>　　接下来m行描述m件事情，每行包含3个整数Si,Ei,Pi。<br></p> 

 
 # 输出格式 
<p>
　　仅包含一行，为chnlkw在这一天内所能获得最大价值。<br><br></p> 

 
 # 提示 
<p>
数据规模：<br>　　对于30％的数据m <= 10<br>　　对于100％的数据m <= 6000<br>　　对于50%的数据 n <= 6000<br>　　对于100%的数据n <= 100000<br>　　所有输出均小于maxlongint。<br></p> 
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
3
1 3 1
2 4 4
4 4 2
</td><td>4
</td></tr></table>
