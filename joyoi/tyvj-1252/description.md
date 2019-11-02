# 

 
 # 题目描述 
huyichen和xuzhenyi在玩一个游戏：他写一个由0和1组成的序列。<BR>huyichen选其中的一段（比如第3位到第5位），问他这段里面有奇数个1<BR>还是偶数个1。xuzhenyi回答你的问题，然后huyichen继续问。<BR>xuzhenyi有可能在撒谎。huyichen要检查xuzhenyi的答案，指出在xuzhenyi的第几个回答一定有问题。<BR>有问题的意思就是存在一个01序列满足这个回答前的所有回答，而且不存在序列<BR>满足这个回答前的所有回答及这个回答。 

 
 # 输入格式 
第1行一个整数，是这个01序列的长度（&lt;=1000000000)<BR>第2行一个整数，是问题和答案的个数。(&lt;=10000)<BR>第3行开始是问题和答案，<BR>每行先有两个整数，表示你询问的段的开始位置和结束位置。<BR>然后是xuzhenyi的回答。odd表示有奇数个1，even表示有偶数个1。 

 
 # 输出格式 
输出一行，一个数X,表示存在一个01序列满足第1到第X个回答，<BR>但是不存在序列满足第1到第X+1个回答。如果所有回答都没问题，你就输出<BR>所有回答的个数。 

 
 # 提示 
huyichen 
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
<tr><td>10
5
1 2 even
3 4 odd
5 6 even
1 6 even
7 10 odd</td><td>3</td></tr></table>
