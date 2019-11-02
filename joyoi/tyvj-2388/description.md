# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2388/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM4OC9wcm9ibGVtc19pbWFnZXMvMjc4Mi8xNTA3XzEuanBn.jpg"><br></p> 

 
 # 输入格式 
<p>
输入文件editor.in的第一行是指令条数t，以下是需要执行的t个操作。其中：<br>为了使输入文件便于阅读，Insert操作的字符串中可能会插入一些回车符，请忽略掉它们（如果难以理解这句话，可以参考样例）。<br>除了回车符之外，输入文件的所有字符的ASCII码都在闭区间[32, 126]内。且行尾没有空格。<br><br>这里我们有如下假定：<br>&#61548;	MOVE操作不超过50000个，INSERT和DELETE操作的总个数不超过4000，PREV和NEXT操作的总个数不超过200000。<br>&#61548;	所有INSERT插入的字符数之和不超过2M（1M=1024*1024），正确的输出文件长度不超过3M字节。<br>&#61548;	DELETE操作和GET操作执行时光标后必然有足够的字符。MOVE、PREV、NEXT操作必然不会试图把光标移动到非法位置。<br>&#61548;	输入文件没有错误。<br><br>对C++选手的提示：经测试，最大的测试数据使用fstream进行输入有可能会比使用stdio慢约1秒。<br></p> 

 
 # 输出格式 
<p>
输出文件editor.out的每行依次对应输入文件中每条GET指令的输出。<br></p> 
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
<tr><td>15
Insert 26
abcdefghijklmnop
qrstuv wxy
Move 16
Delete 11
Move 5
Insert 1
^
Next
Insert 1
_
Next
Next
Insert 4
.\/.
Get 4
Prev
Insert 1
^
Move 0
Get 22
</td><td>.\/.
abcde^_^f.\/.ghijklmno</td></tr></table>
