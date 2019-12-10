# 

 
 # 题目描述 
<p>
字符串输出（ispis.pas\c\cpp） <br><br>【问题描述】<br>　　Perica得到了一台古老的可用他的PC控制的针式打印机。当他在玩他的这台古董打印机时，他发现这台打印机支持三种操作：<br>　　SET(X)   将字符X写入主记忆体。<br>　　NEXT(X)  将字符X写入次记忆体。<br>　　WRITE    将记忆体中的字符写在纸上。正常情况下是将主记忆体的内容打印在纸上，当且仅当上一条命令是NEXT时，才将次记忆体的内容打印在纸上。<br>　　例如，下面的8条命令可以输出字符串“AABAA”到纸上：<br>　　SET(A), WRITE, WRITE, SET(B), WRITE, SET(A), WRITE, WRITE<br>　　但是，实际上可以用7条命令完成：<br>　　SET(A), WRITE, WRITE, NEXT(B), WRITE, WRITE, WRITE<br>　　给定需要输出的字符串，写一个程序确定最少需要多少步操作才能完成。<br>　　注意：第一条命令必须是SET。<br></p> 

 
 # 输入格式 
<p>
　　输入文件ispis.in的第一行包含有要输出的字符串。这个字符串由不超过10,000个大写字母组成。50%的数据，字符数不超过25个。</p> 

 
 # 输出格式 
<p>
　　输出文件ispis.out的包含一个数，表示最少需要的步骤数。</p> 

 
 # 提示 
<p>
【输入输出样例解释】<br>　　对于第一组样例，步骤为SET(N), WRITE, WRITE。<br>　　对于第二组样例，步骤为SET(I), WRITE, NEXT(O), WRITE, WRITE, SET(X), WRITE。<br>　　对于第三组样例，步骤为SET(B), WRITE, NEXT(A), WRITE, WRITE, NEXT(C), WRITE, WRITE, SET(A), WRITE, NEXT(C), WRITE, WRITE。<br></p> 
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
<tr><td>【输入样例1】
NN

【输入样例2】
IOIX

【输入样例3】
BABCBACA



</td><td>【输出样例1】
3

【输出样例2】
7

【输出样例3】
13</td></tr></table>
