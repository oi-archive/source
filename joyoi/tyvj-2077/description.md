# 

 
 # 题目背景 
NOIp2012考后欢乐赛第一题 

 
 # 题目描述 
　　Tyvj需要您的帮助！如果它曾经帮助过你……<br>　　Tyvj自2009年创建以来，一直秉承着为用户服务的原则，在制作义务性网站，所有的管理员也是义务服务并没有什么报酬。Tyvj之所以可以在没有任何收益的情况下走到今天，和大家的支持是分不开的。<br>　　今年11月底，Tyvj服务器托管将到期，需要大量资金续费（约Need元）。但是昂贵的服务器维护费用对于管理层来说也是一笔不小的支出。<br>　　如果Tyvj曾经帮助过你，而你也希望它在NOIP2012最后一次有保送的竞赛考试后继续存在下去，继续为OIer服务，就请各位OIer解囊相助。<br>　　如果您赞助超过More元，我们将会把您的Tyvj账号列为系统支持者（之前的系统支持者已经全部清空），并且提供更优质的服务。其他超过Much元的赞助者会在公告公示两个月。<br>　　赞助后请发送邮件到admin@tyvj.cn进行确认，其中必须包括赞助大约时间、Tyvj账号、赞助金额，如果是支付宝方式赞助，还需要发送转款编号。<br><br><br>　　公告发布不久，Tyvj就已经收到了N笔热心人捐来的善款，还没有对数据进行统计、判重和分析，但是Admin正忙着升级服务器系统，所以Admin就找到了你，请你设计一个程序来帮助Admin进行数据的统计和分析。(具体的分析方法见输出格式) 

 
 # 输入格式 
输入共N+1行。<br>第一行为四个正整数N，Need，More，Much，分别表示有N笔善款，服务器的维护费用为Need元，系统支持者的捐款下限More元，公告公示的捐款下限Much元。<br>第二行至第N+1行，每行是一笔善款的两个信息，包含Tyvj账号和善款金额Money(空格隔开)。 

 
 # 输出格式 
如果当前筹得善款还不足够支付昂贵的服务器维护费用，则<br>　　输出"We&nbsp;still&nbsp;need&nbsp;(Money)&nbsp;yuan."(不含引号,均为英文格式,下同)<br>　　这里的(Money)表示还差多少资金。<br><br>如果当前筹得善款已经足够支付昂贵的服务器维护费用，则<br><br>如果没有人符合"系统支持者"的要求，也没有人符合"公告公示"的要求，<br>　　输出"Thanks&nbsp;for&nbsp;all&nbsp;the&nbsp;Contributor!"<br><br>否则<br>　　如果当前有人符合了"系统支持者"的要求，<br>　　　　先输出一行"The&nbsp;System&nbsp;Supporter&nbsp;:"(请注意空格)<br>　　　　接下来按第一关键字为善款金额、降序，第二关键字为账号、升序进行排序(下同)<br>　　　　输出系统支持者的Tyvj账号，每行一个。<br>　　如果没有人符合"系统支持者"的要求，<br>　　　　只输出一行"The&nbsp;System&nbsp;Supporter&nbsp;is&nbsp;NONE."<br><br>　　这里输出一个换行符以便区分系统支持者和公告公示账号。(换行符的Ascii码为10)<br><br>　　如果当前有人符合了"公告公示"的要求，(除去"系统支持者"之外，下同)<br>　　　　先输出一行"The&nbsp;Dispalyed&nbsp;Supporter&nbsp;:"<br>　　　　接下来按上述排序方式输出公告公示的Tyvj账号，每行一个。<br>　　如果没有人符合"公告公示"的要求，<br>　　　　只输出一行"The&nbsp;Dispalyed&nbsp;Supporter&nbsp;is&nbsp;NONE." 

 
 # 提示 
对于100%的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;1000，1&nbsp;&lt;=&nbsp;Money&nbsp;&lt;=&nbsp;10^6<br>对于100%的数据，1&nbsp;&lt;=&nbsp;Much&nbsp;&lt;=&nbsp;More&nbsp;&lt;=&nbsp;Need&nbsp;&nbsp;&lt;=&nbsp;10^9<br><br>提示：本题涉及的Tyvj账号不含空格，不含中文，长度不超过15个字符tjz 
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
<tr><td>[Sample 1]
5 4000 200 100
applepi 2000
lydliyudong 1000
This_poet 500
Zanoes 500
wotf1996 99

[Sample 2]
2 400 200 100
tangjz 100
tangjz 100

[Sample 3]
3 200 200 100
k 99
A 99
c 99
</td><td>[Sample 1]
The System Supporter :
applepi
lydliyudong
This_poet
Zanoes

The Dispalyed Supporter is NONE.

[Sample 2]
We still need 200 yuan.

[Sample 3]
Thanks for all the Contributor!</td></tr></table>
