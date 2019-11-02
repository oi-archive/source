# 

 
 # 题目描述 
Freda发明了传呼机之后，rainbow进一步改进了传呼机发送信息所使用的信号。由于现在是数字、信息时代，rainbow发明的信号用N个自然数表示。为了避免两个人的对话被大坏蛋VariantF偷听T_T，rainbow把对话分成A、B两部分，分别用a、b两个密码加密。现在Freda接到了rainbow的信息，她的首要工作就是解密。Freda了解到，这两部分的密码计算方式如下：<br>在1~N这N个数中，等概率地选取两个数l、r，如果l&gt;r，则交换l、r。把信号中的第l个数到第r个数取出来，构成一个数列P。<br>A部分对话的密码是数列P的“and和”的数学期望值。“and和”就是数列P中各个数做“位与”运算之后得到的数；&nbsp;and和的期望就是对于所有可能选取的l、r，所得到的数列的and和的平均数。<br>B部分对话的密码是数列P的or和的期望，定义类似于and和。<br> 

 
 # 输入格式 
第一行一个正整数N。<br>第二行N个自然数，表示Freda接到的信号。<br> 

 
 # 输出格式 
一行两个实数，分别表示and和、or和的期望，四舍五入保留3位小数，两个实数之间用一个空格隔开。<br> 

 
 # 提示 
数据范围与约定<br>对于20%的数据，1&lt;=N&lt;=100。<br>对于40%的数据，1&lt;=N&lt;=1000。<br>对于另外30%的数据，N个数为0或1。<br>对于100%的数据，1&lt;=N&lt;=100000，N个自然数均不超过10^9。<br><br>样例解释<br>样例1共包含四种可能的l、r：<br>l,&nbsp;r	and和	or和<br>1,1	&nbsp;&nbsp;&nbsp;&nbsp;4	&nbsp;&nbsp;&nbsp;&nbsp;4<br>1,2&nbsp;&nbsp;&nbsp;&nbsp;	4	&nbsp;&nbsp;&nbsp;&nbsp;5<br>2,1	&nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5<br>2,2&nbsp;&nbsp;&nbsp;&nbsp;	5	&nbsp;&nbsp;&nbsp;&nbsp;5<br>以上每一对l、r出现的概率均相同，因此分别对and和、or和取平均数就是数学期望值。<br> 
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
<tr><td>样例输入1
2
4 5

样例输入2
3
1 0 1
</td><td>样例输出1
4.250 4.750

样例输出2
0.222 0.889
</td></tr></table>
