# 

 
 # 题目背景 
蛟川书院模拟测试题 

 
 # 题目描述 
给定两个集合A,B，每个集合中的元素各不相同，如果没有公共元素则输出“A&nbsp;and&nbsp;B&nbsp;are&nbsp;disjoint”，如果B集合中有的A都有，A有的B不一定有则输出“B&nbsp;is&nbsp;a&nbsp;proper&nbsp;subset&nbsp;of&nbsp;A”，如果A集合中有的B都有，B有的A不一定有则输出“A&nbsp;is&nbsp;a&nbsp;proper&nbsp;subset&nbsp;of&nbsp;B”，如果两个集合中的元素完全一一对应，则输出“A&nbsp;equals&nbsp;B”，以上情况均不符合，则输出“I'm&nbsp;confused!” 

 
 # 输入格式 
共两行，第一行第一个正整数n(1&lt;=n&lt;=100000)表示A集合的元素个数，接下来为A集合的n个整数<BR>第二行B集合类似。 

 
 # 输出格式 
只有一行，如题所述的其中一句英文。 

 
 # 提示 
Moe-ing 
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
<tr><td>1 1
2 1 2</td><td>A is a proper subset of B</td></tr></table>
