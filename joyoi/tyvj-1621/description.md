# 

 
 # 题目描述 
badgers是可爱的动物，Manao想拥有一些。宠物店提供N个badgers，编号为1..N，Manao都很喜欢，所以他想拥有得越多越好。初始，每个badger每天需要固定量的食物。但是，如果它看见别的badger也在吃东西，它会觉得饥饿而吃更多的东西。一个badger每多一个同食者需要增加一个固定量的食物。<BR>hungeri表示第i个badger单独进食所需要的食物。greedi表示第i个badger在每多一个同食者的情况下增加的食物量。Manao每天最多可以供应totalFood量的食物，那么他最多可以养多少只badgers。<BR> 

 
 # 输入格式 
第一行两个整数N和totalFood。<BR>第二行N个整数，第i个为Hungeri。<BR>第三行N个整数，第i个为greedi。 

 
 # 输出格式 
一个整数，表示Manao最多可以养多少只badgers。 

 
 # 提示 
30%的数据N&lt;=10。<BR>100%的数据1&lt;=N&lt;=50，1&lt;=hunger&lt;=1000，0&lt;=greed&lt;=1000，1&lt;=totalFood&lt;=1000000。 
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
<tr><td>//样例输入1
3 7
1 2 3
2 2 1
//样例输入2
4 19
5 2 1 5
0 2 4 1
</td><td>样例输出1
2
样例输出2
3</td></tr></table>
