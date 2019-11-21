# 

 
 # 题目描述 
【问题描述】：NBA每年都有球员选秀环节。通常用速度和身高两项数据来衡量一个篮球运动员的基本素质。假如一支球队里速度最慢的球员速度为minV，身高最矮的球员高度为minH，那么这支球队的所有队员都应该满足:<BR>A&nbsp;*&nbsp;(&nbsp;height&nbsp;–&nbsp;minH&nbsp;)&nbsp;+&nbsp;B&nbsp;*&nbsp;(&nbsp;speed&nbsp;–&nbsp;minV&nbsp;)&nbsp;&lt;=&nbsp;C<BR>	其中A和B，C为给定的经验值。这个式子很容易理解，如果一个球队的球员速度和身高差距太大，会造成配合的不协调。<BR>	请问作为球队管理层的你，在N名选秀球员中，最多能有多少名符合条件的候选球员。 

 
 # 输入格式 
【输入】<BR>&nbsp;&nbsp;	第一行四个数N、A、B、C<BR>	下接N行每行两个数描述一个球员的height和speed 

 
 # 输出格式 
【输出】<BR>&nbsp;&nbsp;&nbsp;	最多候选球员数目。 

 
 # 提示 
【数据范围】<BR>		(2&lt;=M&lt;=9,1&lt;=N&lt;=60),&nbsp;(1&lt;=T&lt;=1000)<BR> 
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
<tr><td>【样例输入】
4 1 2 10
5 1
3 2
2 3
2 1</td><td>【样例输出】
4</td></tr></table>
