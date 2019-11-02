# 

 
 # 题目背景 
『Citric杯』NOIP模拟赛&nbsp;I&nbsp;第一题<BR><BR> 

 
 # 题目描述 
某天Lemon去超市买柠檬，他发现货架上有N个柠檬，每个柠檬都有一个重量Wi和价格Ci.<BR>Lemon身上只带了S元钱，因此他想要买一个价格不超过S的柠檬回家，另外，他希望他买的那个柠檬的性价比尽量高。<BR>性价比的定义是重量除以价格，即第i个柠檬的性价比是Wi/Ci.&nbsp;你的任务是告诉Lemon，他应该买第几个柠檬。<BR><BR> 

 
 # 输入格式 
输入文件第一行包含两个正整数N，S<BR>输入文件第2～N+1行，每行包含两个正整数Wi，Ci，第i+1行的数表示第i个柠檬的重量和价格。<BR><BR> 

 
 # 输出格式 
输出文件第一行仅包含一个数K，表示购买第K只柠檬能使Lemon在可以接受的价格内获得最高的性价比。题目保证答案唯一。<BR><BR> 

 
 # 提示 
第1只柠檬重量为4，价格为8，性价比为4/8=0.5<BR>第2只柠檬重量为4，价格为10，性价比为4/10=0.4<BR>第3只柠檬重量为8，价格为10，性加比为8/10=0.8<BR>第4只柠檬重量为10000，价格为20，性价比为10000/20=500，但Lemon只带了15元，无法购买这只柠檬<BR>因此Lemon的最佳选择是第3只柠檬。<BR><BR> 
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
<tr><td>4 15
4 8
4 10
8 10
10000 20

</td><td>3

</td></tr></table>
