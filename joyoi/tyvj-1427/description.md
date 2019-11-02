# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小新经常陪小白去公园玩，也就是所谓的遛狗啦…在小新家附近有一条“公园路”，路的一边从南到北依次排着n个公园，小白早就看花了眼，自己也不清楚该去哪些公园玩了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;一开始，小白就根据公园的风景给每个公园打了分-.-。小新为了省事，每次遛狗的时候都会事先规定一个范围，小白只可以选择第a个和第b个公园之间（包括a、b两个公园）选择<B>连续</B>的一些公园玩。小白当然希望选出的公园的分数总和尽量高咯。同时，由于一些公园的景观会有所改变，所以，小白的打分也可能会有一些变化。<BR>&nbsp;&nbsp;&nbsp;&nbsp;那么，就请你来帮小白选择公园吧。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行，两个整数N和M，分别表示表示公园的数量和操作（遛狗或者改变打分）总数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行一个整数，依次给出小白&nbsp;开始时对公园的打分。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来M行，每行三个整数。第一个整数K，1或2。K=1表示，小新要带小白出去玩，接下来的两个整数a和b给出了选择公园的范围（1≤a,b≤N）；K=2表示，小白改变了对某个公园的打分，接下来的两个整数p和s，表示小白对第p个公园的打分变成了s（1≤p≤N）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;其中，1≤N≤500&nbsp;000，1≤M≤100&nbsp;000，所有打分都是绝对值不超过1000的整数。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;小白每出去玩一次，都对应输出一行，只包含一个整数，表示小白可以选出的公园得分和的最大值。 
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
<tr><td>5 3
1 2 -3 4 5
1 2 3
2 2 -1
1 2 3
</td><td>2
-1
</td></tr></table>
