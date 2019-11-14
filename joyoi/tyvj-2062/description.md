# 

 
 # 题目描述 
&nbsp;葡萄架上有n串葡萄，每串葡萄都有一个价值。<br>有一只狐狸想偷走一些。不过她规定,任意连续的k串葡萄中,最多选b串,最少选a串。<br>现在,狐狸要选出一些葡萄，使得狐狸得到的葡萄的价值和，与剩余葡萄的价值的和，差值最大。<br> 

 
 # 输入格式 
&nbsp;第一行四个整数n,k,a,b<br>一行N个整数表示每串葡萄的价值<br> 

 
 # 输出格式 
&nbsp;一个整数表示答案 

 
 # 提示 
样例解释：<br>得到第一串得到的价值和是2<br>剩余的价值和是-2<br>差值为4<br><br>数据范围：<br>对于20%：n&lt;=10<br>对于另外20%：a=0,b=k<br>对于100%：n&lt;=1000,0&lt;=a&lt;=b&lt;=k&lt;=10&nbsp;&nbsp;&nbsp;k&lt;=&nbsp;n&nbsp;单个葡萄的价值的绝对值&lt;=10^9<br> 
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
<tr><td>2 1 0 1
2 -2
</td><td>4
</td></tr></table>
