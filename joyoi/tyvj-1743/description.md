# 

 
 # 题目背景 
在举世闻名的CCF-NOIP-2011举办期间，TEACHER&nbsp;和&nbsp;STUDENTS&nbsp;们进行了一场空前的大战——SvT。午饭过后……<BR> 

 
 # 题目描述 
午饭过后，大家回到了自己的休息室，而尊敬的Teacher&nbsp;Li则与其他的带队老师（衰哥+MM）聊起了something。大家无聊ing。于是聪明的XXX同学想到了用短信“玩耍”Teacher&nbsp;Li（这也只能怪Teacher&nbsp;Li，让我们带手机……）于是，所有参加比赛的N个同学都给Li发了短信，其中的一些同学给老师发的短信极有特色——告知Teacher某个虚拟人物正在寻找Teacher&nbsp;Li。这类短信包含了“Teacher&nbsp;Li”字串和某个虚拟人物的姓名。而且每条短信（不只是特殊短信）后包含这这个虚拟人物的坐标。（坐标与短信用空格隔开）(任何地方无多余空格)（不含标点符号）<BR>（注意:&nbsp;“Teacher&nbsp;Li”字串和某个虚拟人物的姓名为单独的单词，不是包含于另一单词，不考虑大小写）<BR>你的任务是：找出这类短信的条数，并且分别输出虚拟人物的坐标。坐标(x,y)需要从小到大排序输出（一号关键字x，二号关键字y）。<BR> 

 
 # 输入格式 
第一行：一个字符串S——虚拟人物的姓名<BR>第二行：一个整数N——表示参赛人数<BR>第3——n+2行：每行表示一条短信Si<BR> 

 
 # 输出格式 
第一行：一个整数M：表示共有M条特殊短信<BR>第2——n+1行：每行输出2个整数X,Y，表示排序后的坐标<BR> 

 
 # 提示 
1&lt;姓名长度&lt;200<BR>1&lt;短信长度（包括坐标）&lt;1,000,000<BR>20%&nbsp;0&lt;n&lt;50<BR>50%&nbsp;0&lt;n&lt;1000<BR>100%&nbsp;0&lt;n&lt;10000<BR>0&lt;x,y&lt;9<BR>SUN-2011&nbsp;PAN&nbsp;YUCHONG 
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
<tr><td>Student
3
Dear Teacher Li there is a student 5 3
Teacher Li I am a student 1 1
Teacher Vs Student 8 5
</td><td>2
1 1
5 3
</td></tr></table>
