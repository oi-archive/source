# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;乔帮主走好。<BR>&nbsp;&nbsp;&nbsp;&nbsp;说到Jobs改变世界的第一作，自然是ipod了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在我的ipod上，一共有M首歌，每个歌是属于某个类型xi，播放时间是yi。一共有N个类型。按照我的习惯，在不同类型的歌曲播放之后，只能播放几个固定类型的歌曲，比如在Pop之后，我比较喜欢Classic。试问，播放时长在min~max之间的播放方式有几种。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行两个数M，N。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来M行，每行两个数xi，yi，表示这首歌属于xi类型，时长为yi。<BR>接下来一个N*N的矩阵，第i行第j个元素表示第i个类型的歌后是否可以接第j类型的歌，Y表示可以，N表示不可以。<BR>&nbsp;&nbsp;&nbsp;&nbsp;最后一行两个数min和max。<BR> 

 
 # 输出格式 
一个数也就是不同播放方式的总数，模600921647的值。 

 
 # 提示 
数据规模：<BR>N≤9；y≤9；M≤700；<BR>min&lt;max≤10^9。<BR>30%的数据，max≤10000。<BR>注意事项：<BR>类型和歌曲都是从1开始编号。<BR>样例解释{1},{2},{3,3},{3,3,3},{4},{3,4},{4,3}。<BR>空间限制：64MB清北学堂杯2011NovTyvj月赛(提高组难度)第三题 
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
1 9
2 8
3 3
3 5
YYY
NYY
NNY
5 9</td><td>7</td></tr></table>
