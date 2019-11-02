# 

 
 # 题目描述 
<p>
问题描述：<br>	John先生晚上写了n封信，并相应地写了n个信封将信装好，准备寄出。但是，第二天John的儿子Small John将这n封信都拿出了信封。不幸的是，Small John无法将拿出的信正确地装回信封中了。<br><br>编程任务：<br>	将Small John所提供的n封信依次编号为1，2，…，n；且n个信封也依次编号为1，2，…，n。假定Small John能提供一组信息：第i封信肯定不是装在信封j中。请编程帮助Small John，尽可能多地将信正确地装回信封。</p> 

 
 # 输入格式 
<p>
文件的第一行是一个整数n（n≤100）。信和信封依次编号为1，2，…，n。<br>接下来的各行中每行有2个数i和j，表示第i封信肯定不是装在第j个信封中。文件最后一行是2个0，表示结束。</p> 

 
 # 输出格式 
<p>
输出文件的各行中每行有2个数i和j，表示第i封信肯定是装在第j个信封中。请按信的编号i从小到大顺序输出。若不能确定正确装入信封的任何信件，则输出“none”。</p> 
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
1 2
1 3
2 1
0 0</td><td>1  1</td></tr></table>
