# 

 
 # 题目描述 
<p>
农场中,由于奶牛数量的迅速增长,通往奶牛宿舍的道路也出现了严重的交通拥堵问题.FJ打算找出最忙碌的道路来重点整治. 

 
 # 输入格式 
<p>
第一行:两个用空格隔开的整数:N,M. 

 
 # 输出格式 
<p>
第一行: 一个整数,表示所有路径中通过某条道路的最大次数. 
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
<tr><td>7 7
1 3
3 4
3 5
4 6
2 3
5 6
6 7
</td><td>
4
样例说明: 

    1   4
     \ / \
      3   6 -- 7
     / \ /
    2   5
通向奶牛宿舍的所有路径: 

    1 3 4 6 7
    1 3 5 6 7
    2 3 4 6 7
    2 3 5 6 7