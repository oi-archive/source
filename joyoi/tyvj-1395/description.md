# 

 
 # 题目背景 
NOIP2010普及组复赛第二题<BR> 

 
 # 题目描述 
学校里有一个水房，水房里一共装有m&nbsp;个龙头可供同学们打开水，每个龙头每秒钟的<BR>供水量相等，均为1。<BR>现在有n&nbsp;名同学准备接水，他们的初始接水顺序已经确定。将这些同学按接水顺序从1<BR>到n&nbsp;编号，i&nbsp;号同学的接水量为wi。接水开始时，1&nbsp;到m&nbsp;号同学各占一个水龙头，并同时打<BR>开水龙头接水。当其中某名同学j&nbsp;完成其接水量要求wj&nbsp;后，下一名排队等候接水的同学k<BR>马上接替j&nbsp;同学的位置开始接水。这个换人的过程是瞬间完成的，且没有任何水的浪费。即<BR>j&nbsp;同学第x&nbsp;秒结束时完成接水，则k&nbsp;同学第x+1&nbsp;秒立刻开始接水。若当前接水人数n’不足m，<BR>则只有n’个龙头供水，其它m-n’个龙头关闭。<BR>现在给出n&nbsp;名同学的接水量，按照上述接水规则，问所有同学都接完水需要多少秒。 

 
 # 输入格式 
第1&nbsp;行2&nbsp;个整数n&nbsp;和m，用一个空格隔开，分别表示接水人数和龙头个数。<BR>第2&nbsp;行n&nbsp;个整数w1、w2、……、wn，每两个整数之间用一个空格隔开，wi&nbsp;表示i&nbsp;号同<BR>学的接水量。 

 
 # 输出格式 
输出只有一行，1&nbsp;个整数，表示接水所需的总时间。 

 
 # 提示 
【数据范围】<BR>1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;10000，1&nbsp;≤m≤&nbsp;100&nbsp;且m≤&nbsp;n；<BR>1&nbsp;≤&nbsp;wi&nbsp;≤&nbsp;100。NOIP2010普及组复赛——NO.2 
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
<tr><td>【输入样例1】
5 3
4 4 1 2 1
【输入样例2】
8 4
23 71 87 32 70 93 80 76</td><td>输出样例1:
4
输出样例2:
163
</td></tr></table>
