# 

 
 # 题目描述 
请帮板猪编一个程序来判断一个电路是否短路或断路，斌且计算出有多少灯泡能亮。 

 
 # 输入格式 
第1行，n,m，表示方阵的大小。第2行至第m+1行，每行n个数，表示电路方阵。<BR>‘1’表示导线，‘0‘表示空的，’2‘表示电池，‘3’表示灯泡。其中电池只有一个，其余有无限个。<BR>如：<BR>4&nbsp;4<BR>1&nbsp;1&nbsp;1&nbsp;3<BR>1&nbsp;0&nbsp;0&nbsp;1<BR>1&nbsp;0&nbsp;0&nbsp;1<BR>1&nbsp;2&nbsp;1&nbsp;1<BR>表示如下电路：<BR>----------------(灯泡)<BR>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<BR>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<BR>-----|电池|-----------<BR>电池不分正负极<BR>灯泡短路也算亮<BR>不会存在<BR>1&nbsp;1&nbsp;1&nbsp;1&nbsp;1<BR>1&nbsp;1&nbsp;1&nbsp;1&nbsp;1<BR>的情况 

 
 # 输出格式 
若电路短路或断路，则输出‘Error'，否则输出有多少灯泡能亮。 

 
 # 提示 
其中电池只有一个，其余有无限个。<BR>板猪寄语：我要出名。<BR>管理员添加：100%的数据保证n,m&lt;=10 
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
<tr><td>样例输入1：
4 4
1 1 1 1
1 0 0 1
1 0 0 1
1 2 1 1
样例输入2：
5 5
1 1 1 3 1
1 0 1 0 1
1 3 1 0 1
1 0 1 0 1
1 1 1 2 1</td><td>样例输出1：
Error
样例输出2：
2</td></tr></table>
