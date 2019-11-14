# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;恺撒大帝曾经使用过这样一种加密术：对于明文中的每个字母，恺撒大帝会用它后面的第t个字母代替。例如，当t=3时，字母A将变成C，字母B将变成D，……，字母Y将变成A，字母Z将变成B（假设字母表是循环的）。<br>　　这样一来，字母表：&nbsp;&nbsp;A&nbsp;B&nbsp;C&nbsp;D&nbsp;E&nbsp;F&nbsp;G&nbsp;H&nbsp;I&nbsp;J&nbsp;K&nbsp;L&nbsp;M&nbsp;N&nbsp;O&nbsp;P&nbsp;Q&nbsp;R&nbsp;S&nbsp;T&nbsp;U&nbsp;V&nbsp;W&nbsp;X&nbsp;Y&nbsp;Z<br>　　将变成：　　　　　　C&nbsp;D&nbsp;E&nbsp;F&nbsp;G&nbsp;H&nbsp;I&nbsp;J&nbsp;K&nbsp;L&nbsp;M&nbsp;N&nbsp;O&nbsp;P&nbsp;Q&nbsp;R&nbsp;S&nbsp;T&nbsp;U&nbsp;V&nbsp;W&nbsp;X&nbsp;Y&nbsp;Z&nbsp;A&nbsp;B<br>　　明文：&nbsp;&nbsp;I&nbsp;Love&nbsp;You&nbsp;&nbsp;将加密为<br>　　密文：&nbsp;&nbsp;K&nbsp;Nqxg&nbsp;Aqw<br>　　如此一来，需要传达的信息在外人看来就如同天书了。加上恺撒大帝会不时更换t的值，使得密码变得更加难以捉摸。<br>　　后人称这种加密方法为“恺撒移位密码”&nbsp;&nbsp;<br> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;有消息称：Matrix67找到了自己的Miss&nbsp;Right，正准备自己人生的第一次表白。Matrix67已经写好了情书，但为了避免其它人截获，他打算采用古来的恺撒移位密码进行加密。<br>　　你通过某种渠道获知了Matrix67的加密方式。为了打探Matrix67的私密，你冒着生命危险终于搞到了这封情书。原以为可以轻易将情书解密，结果竟然发现聪明的Matrix67并没有直接写出加密用的t值，而是在那粉红色的信纸背面写着“t=你的幸运数字”。<br>　　就这么放弃了吗？不，作为一个高智商的OIer，你决不轻言放弃。你需要编写一个解密程序，在不知道t值的情况下将原文打印出来。<br> 

 
 # 输入格式 
&nbsp;&nbsp;　输入一段文字。文字中可能包含字母、数字、标点符号、空格、回车、制表符等各种符号，其中只有字母被加密处理过。加密后的字母其大小写不变。<br>&nbsp;<br> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;你的程序需要在不知道t值的情况下解密输入文件并输出明文。<br>　　我们的明文保证是成章的英文段落，没有语法和单词拼写错误。<br> 

 
 # 提示 
10KB&lt;=输入的数据&lt;=50KB 
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
<tr><td>K YKNN UJQY AQW

Agu, K co uvknn cocbgf vjcv K jcxg aqw. Kv'u uvknn jctf vq wpfgtuvcpf jqy aqw ejqug og. Jqy chvgt lwuv qpg ujqtv eqpxgtucvkqp aqw mpgy K ycu ogcpv hqt aqw. Dwv pqy K mpqy vjg vtwvj qh aqwt eqpxkevkqp. K'xg pgxgt dggp ykvj uqogqpg yjq uwkvgf og uq rgthgevna. Aqw ugfwegf og ykvj aqwt ugza dqfa cpf uvtqpi urktkv, cpf aqw'xg mgrv og ykvj aqwt vgpfgt jgctv. K mpqy aqw vjcv K ecp'v jcxg aqw eqorngvgna cpf ocadg pqv gxgp hqt owej nqpigt. Dwv K'o uvknn jcrra. C rctv qh aqw jcu dgeqog rctv qh og cpf vjcv ku gpqwij.


Aqw'nn ncwij yjgp K uca vjku, dwv K ftgco cdqwv aqw gxgta pkijv. Rtqdcdna dgecwug K ecp'v ugg aqw qhvgp gpqwij. Dwv yjgp K'o cycmg K mpqy vjcv aqw ctg vjg hwtvjguv vjkpi htqo c ftgco. Uqogvkogu K kocikpg vjcv aqw ctg dwknv htqo uqnkf tqem: c oqxkpi uvcvwg cpf cp kpfguvtwevkdng jwocp dgkpi. Aqw cduqnwvgna eqpvckp aqwtugnh cpf vjgp cickp owej oqtg vjcp aqwtugnh. Aqwt eqphkfgpeg ku eqpuwokpi cpf aqwt rgturgevkxg ku jwig. Aqw jcxg pq rnceg kp aqwt nkhg hqt lgcnqwua qt eqornckpvu. Oa htkgpfu uggo uq uocnn kp eqorctkuqp, ykvj vjgkt rtqdngou cnycau urknnkpi qxgt qpvq gxgtaqpg gnug.

K ycpv aqw vq mpqy jqy owej aqw'xg qrgpgf oa gagu cpf jgnrgf og vtwna ugg oaugnh. Wpvkn pqy, oa nkhg jcu dggp cp wpfgekfgf dcem-cpf-hqtvj, cpf pqy K mpqy vjcv K'xg ycuvgf vqq owej vkog. Dwv pqy oa fktgevkqp uggou engct, cpf K jcxg eqphkfgpeg kp oa hwvwtg. Vjg rcuv fqgup'v uggo vq ocvvgt cpaoqtg. Aqw'xg ocfg og ugg rquukdknkvkgu K yqwnf pgxgt jcxg kocikpgf dghqtg.

Agu, K ycpv vq rngcug aqw. Dwv kv'u vjtqwij rngcukpi aqw vjcv K'nn dgeqog c dgvvgt cpf uvtqpigt rgtuqp. Vjgtg ku pqvjkpi K ycpv oqtg vjcp vq vtcpuhqto oaugnh vjtqwij aqw. Aqw ejcnngpig og vq itqy dgaqpf oaugnh cpf ngcxg oa ygcmgt ugnh dgjkpf. K yknn ujqy aqw jqy dgcwvkhwn K ecp dg, cpf K yknn ujqy aqw jqy dtknnkcpv K ecp dgeqog. Vjku yca, K mpqy K'nn cnycau jcxg aqwt nqxg.

Hqtgxgt aqwtu,

Ocvtkz67
</td><td>I WILL SHOW YOU

Yes, I am still amazed that I have you. It's still hard to understand how you chose me. How after just one short conversation you knew I was meant for you. But now I know the truth of your conviction. I've never been with someone who suited me so perfectly. You seduced me with your sexy body and strong spirit, and you've kept me with your tender heart. I know you that I can't have you completely and maybe not even for much longer. But I'm still happy. A part of you has become part of me and that is enough.


You'll laugh when I say this, but I dream about you every night. Probably because I can't see you often enough. But when I'm awake I know that you are the furthest thing from a dream. Sometimes I imagine that you are built from solid rock: a moving statue and an indestructible human being. You absolutely contain yourself and then again much more than yourself. Your confidence is consuming and your perspective is huge. You have no place in your life for jealousy or complaints. My friends seem so small in comparison, with their problems always spilling over onto everyone else.

I want you to know how much you've opened my eyes and helped me truly see myself. Until now, my life has been an undecided back-and-forth, and now I know that I've wasted too much time. But now my direction seems clear, and I have confidence in my future. The past doesn't seem to matter anymore. You've made me see possibilities I would never have imagined before.

Yes, I want to please you. But it's through pleasing you that I'll become a better and stronger person. There is nothing I want more than to transform myself through you. You challenge me to grow beyond myself and leave my weaker self behind. I will show you how beautiful I can be, and I will show you how brilliant I can become. This way, I know I'll always have your love.

Forever yours,

Matrix67

</td></tr></table>
