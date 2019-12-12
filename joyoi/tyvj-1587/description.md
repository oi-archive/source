# 

 
 # 题目背景 
音乐是储存记忆最好的方式，你的一切于我来说，始于音符，终于和弦。 

 
 # 题目描述 
作为一名专业的吉他手，深绘里经常在空闲的时候来研究和弦的构成。<BR>她把一个和弦定义为包含n个音符的序列，而且每个音符都有一个频率值。为了使音乐更加动听，深绘里规定，一个和弦里第i个音符的频率值必须小于第i+2(如果存在）和第i+3(如果存在）个音符的频率值。<BR>而且对于一个包含n个音符的和弦，每个音符的频率值都是一个属于[1,n]的正整数。<BR>现在深绘里想知道给定一个正整数n，共有多少种不同的和弦呢。<BR>注意两个和弦不同，当且仅当存在一个位置，这两个和弦此位置上的音符频率值不相同。<BR> 

 
 # 输入格式 
一个正整数n<BR> 

 
 # 输出格式 
一行一个数，表示不同和弦的种类数。结果对4294967296取模。<BR> 

 
 # 提示 
对于20%的数据，1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;50<BR>对于50%的数据，1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;300<BR>对于100%的数据，1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;1000<BR><BR>样例共有9种合法的序列，分别为<BR>1&nbsp;1&nbsp;3<BR>1&nbsp;2&nbsp;3<BR>1&nbsp;3&nbsp;3<BR>1&nbsp;1&nbsp;2<BR>1&nbsp;2&nbsp;2<BR>1&nbsp;3&nbsp;2<BR>2&nbsp;1&nbsp;3<BR>2&nbsp;2&nbsp;3<BR>2&nbsp;3&nbsp;3<BR>Vani 
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
</td><td>9
</td></tr></table>
