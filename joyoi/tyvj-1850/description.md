# 

 
 # 题目描述 
N个布丁摆成一行,进行M次操作.每次将某个颜色的布丁全部变成另一种颜色的,然后再询问当前一共有多少段颜色.例如颜色分别为1,2,2,1的四个布丁一共有3段颜色. 

 
 # 输入格式 
第一行给出N,M表示布丁的个数和好友的操作次数.&nbsp;第二行N个数A1,A2...An表示第i个布丁的颜色从第三行起有M行,对于每个操作,若第一个数字是1表示要对颜色进行改变，其后的两个整数X,Y表示将所有颜色为X的变为Y，X可能等于Y.&nbsp;若第一个数字为2表示要进行询问当前有多少段颜色，这时你应该输出一个整数. 

 
 # 输出格式 
针对第二类操作即询问，依次输出当前有多少段颜色. 

 
 # 提示 
0&lt;n,m&lt;100001;0&lt;ai,x,y&lt;1000000 
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
<tr><td>4 3
1 2 2 1
2
1 2 1
2</td><td>3
1
</td></tr></table>
