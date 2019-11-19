# 

 
 # 题目背景 
各位一次AC大帝们，这个笔试考试，将是你们的一次AC的终结！！ 

 
 # 题目描述 
小明要读程序了。<BR>程序是go语言。<BR>go语言的程序有两类语句，顺序执行语句和跳转语句。跳转语句的格式为：go&nbsp;行号，作用是跳到行号所指的那一行去执行。&nbsp;顺序语句执行后不会对程序的执行顺序作任何改变。<BR>比如下面的这个程序：<BR>sdkgf<BR>shut&nbsp;up<BR>go&nbsp;5<BR>go&nbsp;2<BR>flokhs<BR>idjhfgh<BR>这个程序一共有&nbsp;6&nbsp;条语句，其中第三和第四条是跳转语句。<BR>程序从第一行开始执行，&nbsp;执行到第三行后就跳到第五行执行，&nbsp;执行到第六行后程序结束。<BR>你的任务是编写一个程序，判断一个go程序会执行多少行语句后退出，或者会进入死循环。<BR>&nbsp; 

 
 # 输入格式 
【输入数据】<BR>第一行是一个数字&nbsp;n，表示程序行数(1&lt;=n&lt;=200)&nbsp;<BR>下面的&nbsp;n&nbsp;行，每行是一条语句，语句前没有多余空格。 

 
 # 输出格式 
【输出数据】<BR>一个数字，表示程序执行的行数。如果程序进入了死循环，则输出数字&nbsp;-1。 

 
 # 提示 
纯模拟有小问题~~请注意~~ 
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
<tr><td>6
sdkgf
shut up
go 5
go 2
flokhs
idjhfgh</td><td>5</td></tr></table>
