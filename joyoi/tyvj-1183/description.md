# 

 
 # 题目描述 
WGSZ举办了一次联谊会,有N个男生和N个女生参加.这次的联谊会安排了一个小节目,好让每个加者都可以找到心仪的对象,小节目的流程如下:<BR>1.每个参加者都有一个编号,且保证一个号码有且仅出现2次,代表一个男生和一个女生拥有相同的编号.这2N个参赛者拿到自己的号码后就会顺序进入一个队列.该队列将在输入之中给出.<BR>2.每个人都要去找跟自己编号相同的异性,但是找的时候每次只能和自己的左右两边的人交换位置.例如:1&nbsp;2&nbsp;3&nbsp;1&nbsp;2&nbsp;3这样一个队列,处在第4号的编号为1的人只能和他左边的第三号位的人交换或者和第五号位的交换位置.不可跨越换位<BR>3.如果一个人找到了和自己编号相同的异性,那么这两个人就高高兴兴的去舞池跳舞去了,此时这两人会迅速离队,后面的人会填充这时空缺的位置.<BR><BR>由于人数众多,主办方希望总交换位置的次数尽量小,所以,主办方找到了你,希望你能帮他解决这个问题.<BR> 

 
 # 输入格式 
第一行:1个数&nbsp;N&nbsp;表示一共有N个编号&nbsp;2N个人参加<BR>以下2*N行:每行一个数&nbsp;代表处于第i号的人的编号 

 
 # 输出格式 
一行:最少的交换次数. 

 
 # 提示 
首先队列是&nbsp;&nbsp;&nbsp;1&nbsp;2&nbsp;3&nbsp;1&nbsp;2&nbsp;3<BR>第一次交换&nbsp;&nbsp;&nbsp;1&nbsp;2&nbsp;3&nbsp;2&nbsp;1&nbsp;3<BR>第二次交换&nbsp;&nbsp;&nbsp;1&nbsp;3&nbsp;2&nbsp;2&nbsp;1&nbsp;3<BR>此时可以消去&nbsp;1&nbsp;3&nbsp;1&nbsp;3<BR>第三次交换&nbsp;&nbsp;&nbsp;1&nbsp;1&nbsp;3&nbsp;3<BR>此时可以消去&nbsp;3&nbsp;3<BR>此时可以消去&nbsp;//<BR>所以最少交换次数为3<BR><BR>数据规模:<BR>10%的数据&nbsp;N&lt;=5<BR>30%的数据&nbsp;N&lt;=10&nbsp;且保证答案在10以内<BR>60%的数据&nbsp;N&lt;=100<BR>100%的数据&nbsp;N&lt;=50000&nbsp;且保证答案在maxlongint范围以内<BR><BR><BR> 
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
1
2
3
1
2
3
</td><td>3
</td></tr></table>
