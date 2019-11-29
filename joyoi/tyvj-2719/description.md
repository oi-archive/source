# 

 
 # 题目描述 
<p>
You must have heard of the literature "Alice's Adventures in Wonderland"! The 3D film "Alice in Wonderland" published by Disney Company becomes the most popular film in 2010! Today, Alice starts her new adventure in Wonderland again!<br><br>In Wonderland, there are n cities, numbered from 1 to n. The capital is city 1. Cities are connected by bi-directional roads. The road system is constructed so that from every city, there is exactly one way to reach any other. <br><br>Alice hopes that she could make a tour in which she visits each city exactly once then return to the capital. Furthermore, she doesn't want to traverse any road more than once. Obviously, it is impossible to make such tour with current road system.<br><br>However, in Wonderland, we can use magic spells! The Cheshire Cat, with his magic power, plans to construct more roads to make Alice's dream come true. Sadly, if he used too many magic spells, he would be weaken. "What is the minimum number of roads I have to construct?" - The poor cat wonders. Could you help him answer this question?<br><br>输入一棵树，添加最少的边使得存在从1开始的哈密尔顿回路</p> 

 
 # 输入格式 
<p>
The first line of input contains the number n --- the number of cities in Wonderland (3 ≤ n ≤ 100 000). The following n-1 lines describe the roads. Each road is represented by two integers --- the indexes of two cities it connects.<br><br></p> 

 
 # 输出格式 
<p>
The minimum number of roads to construct. <br><br></p> 

 
 # 提示 
<p>
In this example, we can construct 2 roads: 3-4 and 4-5, then Alice will be able to take a tour 1-2-3-4-5-1 <br></p> 
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
1 2
2 3
2 4
1 5

</td><td>2</td></tr></table>
