# 

 
 # 题目描述 
<p>
你刚刚继承了流行的“破锣摇滚”乐队录制的尚未发表的N(1 <= N <= 20)首歌的版权。你打算从中精选一些歌曲，发行M(1 <= M <= 20)张CD。每一张CD最多可以容纳T(1 <= T <= 20)分钟的音乐，一首歌不能分装在两张CD中。 <br>不巧你是一位古典音乐迷，不懂如何判定这些歌的艺术价值。于是你决定根据以下标准进行选择： <br> 1.歌曲必须按照创作的时间顺序在CD盘上出现。<br> 2.选中的歌曲数目尽可能地多。<br> 3.不仅同光盘上的歌曲写入时间要按顺序，前一张光盘上的歌曲不能比后一张歌曲写入时间要晚。<br></p> 

 
 # 输入格式 
<p>
第一行： 三个整数：N, T, M. <br>第二行： N个整数，分别表示每首歌的长度，按创作时间顺序排列。 <br></p> 

 
 # 输出格式 
<p>
(file rockers.out) <br>一个整数，表示可以装进M张CD盘的乐曲的最大数目。 <br></p> 
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
<tr><td>4 5 2
4 3 4 2
</td><td>3</td></tr></table>
