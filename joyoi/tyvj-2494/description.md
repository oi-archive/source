# 

 
 # 题目描述 
<p>
没有几个人知道,奶牛有她们自己的字典,里面的有W (1 ≤ W ≤ 600)个词,每个词的长度不超过25,且由小写字母组成.她们在交流时,由于各种原因,用词总是不那么准确.比如,贝茜听到有人对她说"browndcodw",确切的意思是"browncow",多出了两个"d",这两个"d"大概是身边的噪音. <br><br><br>奶牛们发觉辨认那些奇怪的信息很费劲,所以她们就想让你帮忙辨认一条收到的消息,即一个只包含小写字母且长度为L (2 ≤ L ≤ 300)的字符串.有些时候,这个字符串里会有多余的字母,你的任务就是找出最少去掉几个字母就可以使这个字符串变成准确的"牛语"(即奶牛字典中某些词的一个排列). <br><br><br></p> 

 
 # 输入格式 
<p>
第1行:两个用空格隔开的整数,W和L. <br>第2行:一个长度为L的字符串,表示收到的信息. <br>第3行至第W+2行:奶牛的字典,每行一个词. <br></p> 

 
 # 输出格式 
<p>
唯一一行:一个整数,表示最少去掉几个字母就可以使之变成准确的"牛语". <br></p> 
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
<tr><td>
6 10
browndcodw
cow
milk
white
black
brown
farmer

</td><td>
2</td></tr></table>
