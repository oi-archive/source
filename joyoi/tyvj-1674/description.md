# 

 
 # 题目描述 
神犇在经历了无数次学科竞赛的失败以后，得到了一个真理：做一题就要对一题！但是<BR>要完全正确地做对一题是要花很多时间（包括调试时间），而竞赛的时间有限。所以开始做<BR>题之前最好先认真审题，估计一下每一道题完全正确做出来所需要的时间，然后选择一些有<BR>把握的题目先做。<BR>当然，如果做完了预先选择的题目之后还有时间，但是这些时间又不足以完全解决一道<BR>题目，应该把其他的题目用贪心之类的算法随便做做，争取“骗”一点分数。根据每一题解<BR>题时间的估计值，确定一种做题方案（即哪些题目认真做，哪些题目“骗”分，哪些不做），<BR>使能在限定的时间内获得最高的得分， 

 
 # 输入格式 
第一行有两个正整数N&nbsp;和T，表示题目的总数以及竞赛的时限（单位秒）。以下的N&nbsp;行，每行４个正整数W1i&nbsp;、T1i&nbsp;、W2i&nbsp;、T2i&nbsp;，分别表示第i题：完全正确做出来的得分，完全正确做出来所花费的时间（单位秒），“骗”来的分数，“骗”分所花费的时间（单位秒）。 

 
 # 输出格式 
文件只有一行,输出最高得分（包括换行符）。<BR> 

 
 # 提示 
其中，3&nbsp;≤&nbsp;N&nbsp;≤&nbsp;30，2&nbsp;≤&nbsp;T&nbsp;≤&nbsp;1080000，1&nbsp;≤&nbsp;W1i&nbsp;、W2i&nbsp;≤&nbsp;30000，1&nbsp;≤&nbsp;T1i&nbsp;、<BR>T2i&nbsp;≤&nbsp;T。 
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
<tr><td>4 10800
18 3600 3 1800
22 4000 12 3000
28 6000 0 3000
32 8000 24 6000
</td><td>50
</td></tr></table>
