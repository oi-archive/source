# 

 
 # 题目背景 
话说这是NOI夏or冬令营中的水题......<BR>做题前明确的是，这题当然&lt;&gt;n皇后/全排列<BR><BR>这里有n列火车将要进站再出站……<BR>但是，每列火车只有1节---那就是车头……<BR><BR> 

 
 # 题目描述 
有n列火车按1到n的顺序从东方左转进站，这个车站是南北方向的，它虽然无限长，<BR>只可惜是一个死胡同，而且站台只有一条轨道，<BR>火车只能倒着从西方出去，而且每列火车必须进站，先进后出。<BR>（某生：不就是个栈吗？每次可以让右侧头火车进栈，或者让栈顶火车出站？<BR>占卜哥：闭嘴！）<BR>就像这样：<BR>&nbsp;&nbsp;出站&lt;——-&nbsp;&nbsp;&nbsp;&nbsp;&lt;——进站<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|车|<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|站|<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__|<BR>现在请你按《字典序》输出前20种可能的出栈方案。<BR>注意：这题当然不等于全排列！！！ 

 
 # 输入格式 
一个数n&nbsp;N&lt;=20&nbsp;数据保证不会TLE所以千万不要halt<BR> 

 
 # 输出格式 
《字典序》输出前20种答案，每行一种，不要空格 

 
 # 提示 
如果没思路，这道题的出题者“占卜哥”今天仁慈地告诉你，这题可以用栈和深搜来做。。。<BR><BR>这道题的出题者“占卜哥”说了:每当有一列火车车进出站成功,<BR>今天就是您的黄道吉日,RP++；但是如果您做题时程序崩溃,<BR>导致火车进出站中途停止,抱歉,今天您大凶,并且RP--&nbsp;……&nbsp;^_^<BR> 
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
<tr><td>3</td><td>123
132
213
231
321</td></tr></table>
