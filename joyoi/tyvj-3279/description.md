# 

 
 # 题目描述 
<p>
多米诺骨牌<br><br>问题描述：<br>　　一个矩形可以划分成M*N个小正方形，其中有一些小正方形不能使用。一个多米诺骨牌占用两个相邻的小正方形。试问整个区域内最多可以不重叠地放多少个多米诺骨牌且不占用任何一个被标记为无法使用的小正方形。<br></p> 

 
 # 输入格式 
<p>
　　从domino.in中读入数据。<br>　　第一行有两个用空格隔开的正整数M和N。<br>　　第二行有一个正整数K，表示共有K个小正方形不能使用。输入数据保证K <= M*N。<br>　　以下K行每行有两个用空格隔开的数X和Y，表示第X行的第Y个小正方形不能使用。<br></p> 

 
 # 输出格式 
<p>
　　输出最多能放多少个多米诺骨牌。</p> 

 
 # 提示 
<p>
时间限制：<br>　　各测试点1秒<br><br>内存限制：<br>　　你的程序将被分配10MB的运行空间<br><br>数据规模：<br>　　对于30%的数据，M = 1；<br>　　对于50%的数据，M <= 2；<br>　　对于70%的数据，M <= 3；<br>　　对于100%的数据，M <= 50，N <= 50。<br></p> 
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
<tr><td>3 3
2
1 1
2 2

</td><td>3
</td></tr></table>
