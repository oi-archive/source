# 

 
 # 题目描述 
<p>
卡片游戏(cards.pas/c/cpp)<br><br>【问题描述】<br><br>　　有N只moreD在玩一个卡片游戏：<br>　　首先，桌子上有M张卡片，这M张卡片分别有一个唯一的1～M的编号。N只moreD在桌子上抢牌。每个人最后的得分是所得的所有卡片编号的乘积(如果一张卡片都没取，得分为1)。<br>　　这N只moreD最后报出了自己的得分。你的任务是写一个程序，判断有没有人说谎。<br></p> 

 
 # 输入格式 
<p>
输入第一行一个整数T，表示T组测试数据。<br>对于每组测试数据：<br>第一行：两个用空格隔开的整数：N和M，表示moreD的数量和卡片的数量<br>第二行：有N个正整数Ai，表示每只moreD报出的得分。<br></p> 

 
 # 输出格式 
<p>
输出T行，每行输出’Yes’或’No’，表示’Yes’表示不可能没有人说谎 , ’No’表示可能没有人说谎。<br></p> 

 
 # 提示 
<p>
【数据范围】<br>   对于30%的数据N≤3  M≤10 Ai≤100<br>对于100%数据N≤5  M≤100 Ai≤50000 t≤10</p> 
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
<tr><td>3
2 3
2 3
2 3
3 6
2 5
4 6</td><td>No
Yes
No</td></tr></table>
