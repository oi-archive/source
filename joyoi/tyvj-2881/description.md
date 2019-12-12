# 

 
 # 题目描述 
<p>
　　如图所示l，某火车站有B，C两个调度站，左边入口A处有n辆火车等待进站(从左到右以a、b、c、d编号)，右边是出口D，规定在这一段，火车从A进入经过B、C只能从左向右单向开，并且B、C调度站不限定所能停放的车辆数。<br><br><center><img src="/source/joyoi/tyvj-2881/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjg4MS9wcm9ibGVtc19pbWFnZXMvMTIwMy8xLmJtcA==.bmp"></img></center><br>　　从文件输入n及n个小写字母的一个排列，该排列表示火车在出口D处形成的从左到右的火车编号序列。输出为一系列操作过程，每一行形如“h L R”的字母序列，其中h为火车编号，L为h车原先所在位置(位置都以A、B、C、D表示)，R为新位置。或者输出‘NO’表示不能完成这样的调度。<br></p> 

 
 # 输入格式 
<p>
　　一个数n(1 < n < 27 )及由n个小写字母组成的字符串。</p> 

 
 # 输出格式 
<p>
　　可以调度则输出最短的步数，不可以调度时则输出‘NO’。</p> 

 
 # 提示 
<p>
样例的最短调度序列为：<br>c A B<br>b A C<br>a A D<br>b C D<br>c B D<br>共5步完成。<br><br><br>【算法分析】<br>　　这是一道类似于栈的操作题目，只不过是有两个栈B和C可以操作，而对于A序列里的元素，既可以进入B，也可以进入C，或直接到D。解决问题可以从D序列出发反过来看，当前要到D的字符在哪里，如果在A，再看它前面有没有字符，如果有，先让它们进栈(B或C)，否则直接到D；如果在B，看是否是栈顶元素，如果是，直接到D，否则将上面的字符进C；如果在C，看是否是栈顶元素，如果是，直接到D，否则无法进行操作，因为只能向右不能向左，这时要回溯。如果所有的情况都检测过，某个字符不能进行到D的操作，则输出无解信息。<br>　　由于A里的非直接进入D的字符可以进入B或C，可以跟二进制建立起对应关系，将所有情况列举一遍，再找出其中步骤最少的输出。<br></p> 
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
<tr><td>3
cba</td><td>5</td></tr></table>
