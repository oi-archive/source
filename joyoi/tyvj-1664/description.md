# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;中中最近RP极低,他宣传栏上的照片被人扁了很多坑,中中希望他的OIer们将这些坑修复,OIer们为了涨RP迎接NOIP2011也愿意帮助他。但是修复这些坑是一件很复杂的事情。<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;中中的照片上有&nbsp;N&nbsp;个坑,有&nbsp;M&nbsp;个OIer愿意帮助他修补照片,但是每一个OIer所带的修补工具都是不一样的!由于修补工具粗制烂造,会出现两个不同的区域,一个区域是限制域&nbsp;B,还有一个区域是修补域&nbsp;F,并且每个修补工具修补时间不一样（每个修补工具不一定只修补一个坑!!）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;限制域又同时包含两个限制集合,即每一个限制域都有其特定的适用环境,某个修补工具只有在照片中包含某些坑而同时又不包含另一些坑时才可以修补。换句话说,对于每一个修补工具i,都有2个与之相应的限制集合&nbsp;B1[i]&nbsp;和&nbsp;B2[i],使得仅当当前照片上的坑包含&nbsp;B1[i]&nbsp;中的所有坑时,而不包含&nbsp;B2[i]&nbsp;中的任何坑时,才可以使用修补工具&nbsp;i。<BR>&nbsp;&nbsp;&nbsp;&nbsp;修补域也同时包含两个集合,即修补集合和破坏集合。修补集合是将坑修好的集合。破坏集合嘛,就是修补工具制造时所产生的缺陷了,每使用一个修补工具也有可能再制造一些坑。补丁&nbsp;i&nbsp;将修复照片中的某些坑&nbsp;F1[i],而同时加入另一些坑&nbsp;F2[i]。<BR>&nbsp;&nbsp;&nbsp;&nbsp;由于中中学艺不深,所以请你帮帮忙,设计一个程序,算一下将照片上所有坑都修补好的最小的时间。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行包含两个整数&nbsp;N&nbsp;和&nbsp;M&nbsp;,中间有一个空格隔开&nbsp;N&nbsp;和&nbsp;M。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来包含&nbsp;5*M&nbsp;行关于OIer们修补工具的信息:<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i个修补工具<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i*5-3行有一个整数Ti，表示第i个修补工具所用的时间。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i*5-2行有一个数Sb1，表示限制集合B1的元素数量，接下来给出Sb1个数，每两个数中间一个空格，表示B1[i]限制集合中的元素.元素表示的是照片中坑的位置.<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i*5-1行有一个数Sb2，表示限制集合B2的元素数量，接下来给出Sb2个数，每两个数中间一个空格，表示B2[i]限制集合中的元素.元素表示的是照片中坑的位置.<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i*5行有一个数Sf1，表示修补集合F1的元素数量，接下来给出Sf1个数，每两个数中间一个空格，表示F1[i]修补集合中的元素.元素表示的是照片中坑的位置.<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i*5+1行有一个数Sf2，表示破坏集合F2的元素数量，接下来给出Sf2个数，每两个数中间一个空格，表示F2[i]破坏集合中的元素.元素表示的是照片中坑的位置.<BR><BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;仅一个整数表示修补好照片所用的最少的时间。如果无法修补好则输出&nbsp;-1。<BR> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;样例解释:<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;-&gt;&nbsp;2&nbsp;-&gt;&nbsp;1&nbsp;-&gt;&nbsp;3&nbsp;-&gt;&nbsp;1&nbsp;-&gt;&nbsp;2&nbsp;-&gt;&nbsp;1<BR><BR>&nbsp;&nbsp;&nbsp;数据范围：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;50%的数据,&nbsp;N&nbsp;&lt;=10<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100%的数据,&nbsp;N&nbsp;&lt;=20&nbsp;,&nbsp;M&nbsp;&lt;=100<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100%的数据&nbsp;Ti&nbsp;不超过&nbsp;Maxlongint。<BR><BR>&nbsp;&nbsp;&nbsp;每个OIer可以为中中的照片修复无数次。<BR> 
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
<tr><td>3 3
1
0
0
1 3
0
1
0
1 3
1 2
1 3
2
0
2 2 3
1 1
2 2 3
</td><td>8
</td></tr></table>
