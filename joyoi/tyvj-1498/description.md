# 

 
 # 题目背景 
广州市2011年市选第一试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;大家应该听过很多美妙动听的歌曲，也曾经在卡拉OK中唱过不少歌曲。其实，很多歌曲的调子都经过了变调，因为很多歌曲原来的调子一般都偏高，需要把调适当降低，才适合一般人歌唱。现在请你编程解决这个变调的问题，把一个曲谱从原来的调子基础上，升高或降低若干个调，变成一个新的曲谱。<BR>&nbsp;<BR>【音阶】<BR>&nbsp;&nbsp;&nbsp;&nbsp;相信大家都见过电子琴，也听过电子琴，琴中的每个白色键，代表的是简谱中的1,2,3,4,5,6,7的音阶，用字母代表即为&nbsp;C,D,E,F,G,A,B，见下图：<BR>&nbsp;<img src="/source/joyoi/tyvj-1498/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTQ5OC9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL3AxNDk4LmpwZw==.jpg" border=0 align=middle><BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;此外，上面的黑键表示半音，按照上图，从左边到右边的5个黑键代表的半音为：#C,#D,#F,#G,#A<BR>&nbsp;&nbsp;&nbsp;&nbsp;由最左边的音阶C数起到第七个音阶B，中间的黑键和键，均处于一个基准八度区域，在B右边的琴键，比原来的音阶高一个八度区域，称为高八度区域；&nbsp;C音阶左边的琴键（图片没有显示），比原来的音阶低一个八度区域，称为低八度区域。<BR><BR>【乐谱】<BR>&nbsp;&nbsp;&nbsp;&nbsp;一个歌曲的乐谱，包括音阶、节奏、小节线、休止符等元素，这里为了简单表示，只保留音阶这一元素，节奏、小节线、休止符不在此题目中展现。<BR>&nbsp;&nbsp;&nbsp;&nbsp;乐谱中的每个音阶，可以用C,D,E,F,G,A,B,#C,#D,#F,#G,#A&nbsp;表示。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在乐谱中会牵涉到八度区域的迁移问题，我们使用&nbsp;“&gt;”、“&lt;”&nbsp;来变化当前的八度区域。其中“&gt;”表示提高当前八度区域（例如从低八度区域=&gt;基准八度区域），“&lt;”表示降低当前八度区域(例如高八度区域=&gt;基准八度区域)。乐谱一开始的时候，当前八度区域为基准八度区域。<BR><BR>【乐谱变调】<BR>&nbsp;&nbsp;&nbsp;&nbsp;对一个乐谱，提高或者降低N个半音的操作，成为乐谱变调。<BR>&nbsp;&nbsp;&nbsp;&nbsp;首先，对于一个八度区域中，以下音阶均相隔一个半音。<BR>&nbsp;&nbsp;&nbsp;&nbsp;C,#C,D,#D,E,F,#F,G,#G,A,#A,B<BR>&nbsp;&nbsp;&nbsp;&nbsp;然后，B音阶比高它一个八度区域的C音阶，相隔一个半音<BR>&nbsp;&nbsp;&nbsp;&nbsp;变调就是一个简单的升降音阶的操作，只要数着半音阶个数修改音阶即可。例如，C音阶提高6个半音，数过去就是#F，B音阶提高4个音阶，则为下一个八度区域的&nbsp;#D&nbsp;音阶，同理，#F降6个半音阶（升-6个半音）则为C。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入第一行字符串，包含上面的各个音阶，以及&gt;/&lt;符号，表示一个乐谱，乐谱字符串长度&lt;=200，没有空格和其他字符串。<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入第二行为整数N&nbsp;(-16&lt;=N&lt;=16)&nbsp;，表示升多少个半音<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出为一行字符串，代表乐谱。<BR> 
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
<tr><td>CDEFGAB>C
2
</td><td>DE#FGAB>#CD
</td></tr></table>
