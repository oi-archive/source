# 

 
 # 题目背景 
AndyBear&nbsp;生日模拟赛&nbsp;第一题<BR> 

 
 # 题目描述 
BIBO是个贪吃的小熊，她有很多喜欢的食物，但是为了控制体重，她每天不能吃的太多，因此小熊BIBO给每一种食物都赋了一个喜欢程度K，BIBO每天从她所有喜欢的食物中挑出一件喜欢程度最大的来吃，可能是蜂蜜，也可能是面包，同时小熊BIBO还会更改某一种食物的喜欢程度，或者说自己不喜欢某件食物了。你，作为小熊BIBO的首席大管家，要告诉她今天该吃的是什么。<BR> 

 
 # 输入格式 
输入文件的第一行，给出两个数字N和M，分别表示小熊bibo拥有的食物种类以及操作数量。<BR>操作有三种：<BR>Yummy&nbsp;对于每一个Yummy操作，输出一个数字，表示所有食物中喜欢程度的最大值。<BR>Like&nbsp;对于每一个Like操作，后面会跟着一个数对x&nbsp;y，表示小熊bibo把第x种食物的喜欢程度改为了y。<BR>Unlike&nbsp;对于每一个Unlike操作，后面会跟着一个数x，表示小熊bibo不再喜欢第x种食物了，你可以认为这种食物的喜欢程度变成了负无穷。但是请注意，bibo是个善变的小熊，她有可能在之后的某次操作中又喜欢上了这种食物。<BR><BR>输入数据保证，不会出现所有食物都不喜欢的情况。 

 
 # 输出格式 
若干行数字，每一行对应一个Yummy操作的输出。 

 
 # 提示 
在一开始，所有的食物的喜欢程度都为0。<BR>在数据中，0&lt;=喜欢程度K&lt;=1000000.<BR>对于80%的数据&nbsp;0&lt;n,m&lt;=1000<BR>对于100%的数据&nbsp;0&lt;n,m&lt;=100000<BR> 
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
<tr><td>10 6
Yummy
Like 5 100
Yummy
Like 6 99
Unlike 5
Yummy
</td><td>0
100
99
</td></tr></table>
