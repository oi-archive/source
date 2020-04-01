# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2362/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM2Mi9wcm9ibGVtc19pbWFnZXMvMjc0OC8xNDcyLmpwZw==.jpg"><br></p> 

 
 # 输入格式 
<p>
输入第一行一个整数N, 代表有N个骨牌.<br>以下N行每行两个数Pi Hi, 分别表示第I个骨牌的位置和高度. <br></p> 

 
 # 输出格式 
<p>
输出仅一行, 表示最少推倒骨牌的数目</p> 
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
<tr><td>6
1 1
2 2
3 1
5 1
6 1
8 3
</td><td>2


Explanation
              |
  |           |
| | |   | |   |
1 2 3 4 5 6 7 8

Pushing 1 causes 2 and 3 to fall, while pushing 8 causes 6 to fall and gently makes 5 tip over as well.</td></tr></table>
