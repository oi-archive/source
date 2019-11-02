# 

 
 # 题目背景 
<p>noip2013day2</p> 

 
 # 题目描述 
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt;"><span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">春春幼儿园举办了一年一度的&ldquo;积木大赛&rdquo;。今年比赛的内容是搭建一座宽度为n的</span><span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">大</span><br />
<span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">厦，大厦可以看成由n块宽度为1的积木组成，第n块积木的最终高度需要是ℎi,</span><br />
<span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">在搭建开始之前，没有任何积木（可以看成n块高度为&nbsp;0&nbsp;的积木）。接下来每次操作，</span><br />
<span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">小朋友们可以选择一段连续区间[L,R]，然后将第L块到第R块之间（含第&nbsp;L&nbsp;块和第&nbsp;R&nbsp;块）所有积木的高度分别增加1。</span><br />
<span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">小M个聪明的小朋友，她很快想出了建造大厦的最佳策略，使得建造所需的操作次数</span><br />
<span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">最少。但她不是一个勤于动手的孩子，所以想请你帮忙实现这个策略，并求出最少的操作次</span><br />
<span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">数。</span><span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;"><o:p></o:p></span></p> 

 
 # 输入格式 
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt;"><span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">输入包含两行，第一行包含一个整数n,表示大厦的宽度。</span><br />
<span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">第二行包含n个整数，第i个整数为ℎi</span><span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;"><o:p></o:p></span></p> 

 
 # 输出格式 
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt;"><span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;">仅一行，即建造所需的最少操作数。</span><span style="letter-spacing: 0pt; font-family: sans-serif; font-size: 9.5pt;"><o:p></o:p></span></p> 

 
 # 提示 
<p>对于&nbsp;30%的数据，有1&nbsp;&le;n&nbsp;&le;&nbsp;10；<br />
对于&nbsp;70%的数据，有1&nbsp;&le;n&nbsp;&le;&nbsp;1000；<br />
对于&nbsp;100%的数据，有1&nbsp;&le;n&nbsp;&le;&nbsp;100000，&nbsp;0&nbsp;&le;&nbsp;ℎi&le;&nbsp;10000。</p>

<p>by&nbsp;460289052</p> 
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
<tr><td>5
2 3 4 1 2
</td><td>5
</td></tr></table>
