# 

 
 # 题目描述 
<p>
Farmer John最近发明了一个游戏，来考验自命不凡的贝茜。游戏开始的时 <br>候，FJ会给贝茜一块画着N (2 <= N <= 200)个不重合的点的木板，其中第i个点 <br>的横、纵坐标分别为X_i和Y_i (-1,000 <= X_i <=1,000； <br>-1,000 <= Y_i <= 1,000)。 <br><br>贝茜可以选两个点画一条过它们的直线，当且仅当平面上不存在与画出直线 <br>平行的直线。游戏结束时贝茜的得分，就是她画出的直线的总条数。为了在游戏 <br>中胜出，贝茜找到了你，希望你帮她计算一下最大可能得分。 <br></p> 

 
 # 输入格式 
<p>
* 第1行: 输入1个正整数：N <br>* 第2..N+1行: 第i+1行用2个用空格隔开的整数X_i、Y_i，描述了点i的坐标 <br></p> 

 
 # 输出格式 
<p>
第1行: 输出1个整数，表示贝茜的最大得分，即她能画出的互不平行的直线数 <br></p> 

 
 # 提示 
<p>
<br>4<br><br>输出说明:<br><br>    贝茜能画出以下4种斜率的直线：-1，0，1/3以及1。<br><br></p> 
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
<tr><td>4
-1 1
-2 0
0 0
1 1
</td><td>* 第1行: 输出1个整数，表示贝茜的最大得分，即她能画出的互不平行的直线数
</td></tr></table>
