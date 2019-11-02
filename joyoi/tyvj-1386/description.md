# 

 
 # 题目背景 
『天空中的罪恶开始消弭<BR>&nbsp;&nbsp;云和霞光重新枝繁叶茂<BR>&nbsp;&nbsp;六弦琴在诗人手中低声吟唱<BR>&nbsp;&nbsp;歌颂芙蕾雅的恩惠终章。』<BR><BR>————《瓦尔基里福音书·第十乐章：重生》———— 

 
 # 题目描述 
勇士Tristan终于来到了世界树Yggrasil的脚下。作为世界的支柱，Yggrasil上的神祇们为Tristan设下了考验。Yggrasil将Tristan瞬间传送到了顶端，并把自己虚无化为N根横置于直角坐标系上的树枝。树枝有两个参数：左端点坐标和右端点坐标。所有树枝平行于X轴。Tristan一开始位于最上面的一根树枝的左端点。落到到每根树枝上后，他可以选择向左或向右走，但在同一根树枝上不得改变方向。Tristan的跑步速度和下落速度均为1单位长度/s。同时Tristan不能下落超过MaxHigh，否则他会摔死。Tristan已经看到他的伙伴们——Authur和Lancelot他们在树干上等他了，他必须尽快。你能帮他算出最短的落到X轴上的时间吗？ 

 
 # 输入格式 
输入第一行一个整数N。表示树枝根数。第二行到第N+1行每行三个整数x1,x2,y，表示这根树枝的左端横坐标，右端横坐标和高度（纵坐标）。第N+2行一个整数MaxHigh表示Tristan的最大下落高度。 

 
 # 输出格式 
一行一个整数ans，表示Tristan落到X轴所需最短时间。若不管怎么样Tristan都会摔死，输出TP。 

 
 # 提示 
对于100%的数据，1&lt;=N&lt;=100000。所有输入数据绝对值不超过maxlongint,所有树枝均位于X轴上方，树枝之间不会有点重叠或线重叠。《末世神话：忠诚之律》 
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
<tr><td>2
1 3 2
1 1 1
2</td><td>2</td></tr></table>
