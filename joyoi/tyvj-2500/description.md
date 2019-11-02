# 

 
 # 题目描述 
<p>
FJ打算带着他可爱的N (1 ≤ N ≤ 2,000)头奶牛去参加”年度最佳老农”的比赛.在比赛中,每个农夫把他的奶牛排成一列,然后准备经过评委检验. <br><br>比赛中简单地将奶牛的名字缩写为其头字母(the initial letter of every cow),举个例子,FJ带了Bessie, Sylvia,和Dora,那么就可以缩写为BSD. <br><br>FJ只需将奶牛的一个序列重新排列,然后参加比赛.他可以让序列中的第一头奶牛,或者最后一头走出来,站到新队列的队尾. <br><br>利欲熏心的FJ为了取得冠军,他就必须使新队列的字典序尽量小. <br><br>给你初始奶牛序列(用头字母)表示,然后按照上述的规则组成新序列,并使新序列的字典序尽量小. <br></p> 

 
 # 输入格式 
<p>
第1行:一个整数N. <br>第2行至第N+1行:每行一个大写字母,表示初始序列中该奶牛的头字母. <br></p> 

 
 # 输出格式 
<p>
得到的最小字典序的序列.每输出80个字母需要一个换行! <br></p> 
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
A
C
D
B
C
B
</td><td>
ABCBCD</td></tr></table>
