# 

 
 # 题目背景 
NOI2010&nbsp;&nbsp;DAY1&nbsp;&nbsp;NO.2<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小Z是一个小有名气的钢琴家，最近C博士送给了小Z一架超级钢琴，小Z希望能够用这架钢琴创作出世界上最美妙的音乐。&nbsp;<BR>这架超级钢琴可以弹奏出n个音符，编号为1至n。第i个音符的美妙度为Ai，其中Ai可正可负。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;一个"超级和弦"由若干个编号连续的音符组成，包含的音符个数不少于L且不多于R。我们定义超级和弦的美妙度为其包含的所有音符的美妙度之和。两个超级和弦被认为是相同的，当且仅当这两个超级和弦所包含的音符集合是相同的。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;小Z决定创作一首由k个超级和弦组成的乐曲，为了使得乐曲更加动听，小Z要求该乐曲由k个不同的超级和弦组成。我们定义一首乐曲的美妙度为其所包含的所有超级和弦的美妙度之和。小Z想知道他能够创作出来的乐曲美妙度最大值是多少。&nbsp;<BR><BR> 

 
 # 输入格式 
输入文件第一行包含四个正整数n,&nbsp;k,&nbsp;L,&nbsp;R。其中n为音符的个数，k为乐曲所包含的超级和弦个数，L和R分别是超级和弦所包含音符个数的下限和上限。&nbsp;<BR>接下来n行，每行包含一个整数Ai，表示按编号从小到大每个音符的美妙度。&nbsp;<BR><BR> 

 
 # 输出格式 
输出文件只有一个整数，表示乐曲美妙度的最大值。<BR> 

 
 # 提示 
共有5种不同的超级和弦：<BR>1.	音符1&nbsp;~&nbsp;2，美妙度为3&nbsp;+&nbsp;2&nbsp;=&nbsp;5&nbsp;<BR>2.	音符2&nbsp;~&nbsp;3，美妙度为2&nbsp;+&nbsp;(-6)&nbsp;=&nbsp;-4&nbsp;<BR>3.	音符3&nbsp;~&nbsp;4，美妙度为(-6)&nbsp;+&nbsp;8&nbsp;=&nbsp;2&nbsp;<BR>4.	音符1&nbsp;~&nbsp;3，美妙度为3&nbsp;+&nbsp;2&nbsp;+&nbsp;(-6)&nbsp;=&nbsp;-1&nbsp;<BR>5.	音符2&nbsp;~&nbsp;4，美妙度为2&nbsp;+&nbsp;(-6)&nbsp;+&nbsp;8&nbsp;=&nbsp;4&nbsp;<BR>最优方案为：乐曲由和弦1，和弦3，和弦5组成，美妙度为5&nbsp;+&nbsp;2&nbsp;+&nbsp;4&nbsp;=&nbsp;11。<BR>【数据规模和约定】<BR>总共10个测试点，数据范围满足：<BR>&nbsp;<img src="/source/joyoi/tyvj-1256/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI1Ni9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzEyNTYuanBn.jpg" border=0 align=middle><BR>所有数据满足：-1000&nbsp;≤&nbsp;Ai&nbsp;≤&nbsp;1000，1&nbsp;≤&nbsp;L&nbsp;≤&nbsp;R&nbsp;≤&nbsp;n且保证一定存在满足要求的乐曲。<BR><BR><BR><BR> 
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
<tr><td>4 3 2 3
3
2
-6
8


</td><td>11
</td></tr></table>
