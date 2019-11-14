# 

 
 # 题目描述 
题目背景<br>&nbsp;&nbsp;&nbsp;&nbsp;《思远高考绿色通道》(Green&nbsp;Passage,&nbsp;GP)是唐山一中常用的练习册之一，其题量之大深受lsz等许多oiers的痛恨，其中又以数学绿色通道为最。2007年某月某日，soon-if&nbsp;(数学课代表)，又一次宣布收这本作业，而lsz还一点也没有写……<br>题目描述<br>&nbsp;&nbsp;&nbsp;&nbsp;高二数学《绿色通道》总共有n道题目要写(其实是抄)，编号1..n，抄每道题所花时间不一样，抄第i题要花a[i]分钟。由于lsz还要准备NOIP，显然不能成天写绿色通道。lsz决定只用不超过t分钟时间抄这个，因此必然有空着的题。每道题要么不写，要么抄完，不能写一半。一段连续的空题称为一个空题段，它的长度就是所包含的题目数。这样应付自然会引起马老师的愤怒。马老师发怒的程度(简称发怒度)等于最长的空题段长度。<br>&nbsp;&nbsp;&nbsp;&nbsp;现在，lsz想知道他在这t分钟内写哪些题，才能够尽量降低马老师的发怒度。由于lsz很聪明，你只要告诉他发怒度的数值就可以了，不需输出方案。(快乐融化：那么lsz怎么不自己写程序？lsz：我还在抄别的科目的作业……)<br> 

 
 # 输入格式 
第一行为两个整数n,t，代表共有n道题目，t分钟时间。<br>以下一行，为n个整数，依次为a[1],&nbsp;a[2],...&nbsp;a[n]，意义如上所述。<br> 

 
 # 输出格式 
输出仅一行，一个整数w，为最低的发怒度。<br> 

 
 # 提示 
数据规模<br>&nbsp;&nbsp;&nbsp;&nbsp;60%数据&nbsp;n&lt;=2000<br>&nbsp;&nbsp;&nbsp;&nbsp;100%数据&nbsp;0&lt;n&lt;=50000，0&lt;a[i]&lt;=3000，0&lt;t&lt;=100000000<br>样例解释<br>&nbsp;&nbsp;&nbsp;&nbsp;分别写第4,6,10,14题，共用时2+3+3+3=11分钟。空题段：1-3(长度为3),&nbsp;5-5(1),&nbsp;7-9(3),&nbsp;11-13(3),&nbsp;15-17(3)。所以发怒度为3。可以证明，此数据中不存在使得发怒度&lt;=2的作法。<br><br> 
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
<tr><td>17 11
6 4 5 2 5 3 4 5 2 3 4 5 2 3 6 3 5

</td><td>3
</td></tr></table>
