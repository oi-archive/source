# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;有一个奶牛队列…… 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;为了避免餐厅过分拥挤，FJ要求奶牛们分若干批就餐。每天晚饭前，奶牛们都会在餐厅前排队入内，由于奶牛们不理解FJ的安排，晚饭前的排队成了一个大麻烦。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i头奶牛有一张标明她用餐批次D_i(-maxlongint&nbsp;&lt;&nbsp;=&nbsp;D_i&nbsp;&lt;&nbsp;=&nbsp;maxlongint)的卡片。虽然所有N(1&nbsp;&lt;&nbsp;=&nbsp;N&nbsp;&lt;&nbsp;=&nbsp;100,000)头奶牛排成了很整齐的队伍，但谁都看得出来，卡片上的号码是完全杂乱无章的。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在若干次混乱的重新排队后，FJ找到了一种简单些的方法：奶牛们不动，他沿着队伍从头到尾走一遍，把那些他认为排错队的奶牛卡片上的编号改掉，最终得到一个他想要的每个组中的奶牛都站在一起的队列（从小到大），例如1.1.2.2.2.5或-1.1.1.1.2.2。有的时候，FJ会把整个队列弄得只有1组奶牛（比方说，1.1.1.1或2.2.2）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你也晓得，FJ是个很懒的人。他想知道，如果他想达到目的，那么他最少得改多少头奶牛卡片上的编号。所有奶牛在FJ改卡片编号的时候，都不会挪位置。<BR> 

 
 # 输入格式 
*&nbsp;第1行:&nbsp;1个整数：N<BR>*&nbsp;第2..N+1行:&nbsp;第i+1行是1个整数，为第i头奶牛的用餐批次D_i<BR> 

 
 # 输出格式 
输出1个整数，为FJ最少要改几头奶牛卡片上的编号，才能让编号变成他设想中的样子<BR> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一共有7头奶牛，其中有3头奶牛原来被设定为第二批用餐。<BR>输出说明:<BR>FJ选择改第1头和最后1头奶牛卡片上的编号。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;改编自usaco，许多地方有改动，请认真看题。<BR> 
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
<tr><td>7
2
1
1
1
2
2
1
</td><td>2
</td></tr></table>
