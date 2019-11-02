# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;｛*总背景*｝<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一年多前……<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;已经超负荷微子能量核心开始剧烈地颤动。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“要爆炸了，”TL大声地喊道，“快走……”这是，TL才发现，TT已经不见了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一道巨大的弧光划破星云。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“希望宇宙和平到永远！”PL欣慰地说。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“不，还没有结束。”HF说。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“将军，刚才在爆炸附近发现强电流……”<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“他们穿越了空间？”PL问。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HF：“不，是时间！”<BR>&nbsp;&nbsp;&nbsp;&nbsp;{来自&nbsp;P1223&nbsp;微子危机——幻核&nbsp;背景}<BR>&nbsp;&nbsp;&nbsp;&nbsp;蓝紫色的光辉在3003年的一颗不知名的巨大星球上闪现，刺痛了plane运货公司的wg的眼睛。<BR>&nbsp;&nbsp;&nbsp;&nbsp;“这是什么！？”wg一边遮住眼睛，一边问它的宠物——一只乌龟。<BR>&nbsp;&nbsp;&nbsp;&nbsp;光芒逐渐消失，一只庞大的飞船显现在wg和它的乌龟的眼前，乌龟和他的主人wg一样张大了嘴，他们从没见过这么奇异的景象。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这时候，飞船里打开了一扇门，一座楼梯慢慢伸出。<BR>&nbsp;&nbsp;&nbsp;&nbsp;一个穿着宽松的防核服的人低着头走了出来：“我是那么容易被打败的吗？”<BR>&nbsp;&nbsp;&nbsp;&nbsp;他抬起了头，浅浅的笑挂在这个控制欲极强的人——TT的脸上。<BR>&nbsp;&nbsp;&nbsp;&nbsp;{总背景完}<BR>&nbsp;&nbsp;&nbsp;&nbsp;“近年来都发生了什么？”TT向他最新研发的机器人问道，“我是指我穿越的这些年间。”<BR>&nbsp;&nbsp;&nbsp;&nbsp;机器人一字一顿的说，“第一，TT沉睡了几年……”“废话，这还用你说！我难道不知道！”TT愤怒地打断了机器人的发言，“我是说我不知道的！”<BR>&nbsp;&nbsp;&nbsp;&nbsp;机器人想了一想，说：“第一千零八十，3003年新年是末日的传说被……”<BR>&nbsp;&nbsp;&nbsp;&nbsp;“没有建设性的你就不要说了，说一些对我有用的！”TT的脸已经涨得通红。<BR>&nbsp;&nbsp;&nbsp;&nbsp;机器人还是没有语气和表情地说：“第一千零八十三，DG_VS恐怖组织被捣毁……”<BR>&nbsp;&nbsp;&nbsp;&nbsp;“噼里啪啦！”TT的忍耐度终于到了极限，他手里拿着机器人的脑袋：“还是我自己来吧。”<BR>&nbsp;&nbsp;&nbsp;&nbsp;TT决定首先从解析科技工作室的密码开始。<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;对于一种机器，科技工作室往往会将机器的参数加密后储存在一串字符和一串数值里，然后随便发送给一些人，这些人中有些人（科技人员）知道解密方式，但另一些人会把它当做垃圾邮件，TT要做的就是解析这些字符和数值。<BR>&nbsp;&nbsp;&nbsp;&nbsp;密码的形式是:<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;先一个长度为N字符串S，例如abas@@#&nbsp;(&nbsp;N&nbsp;=&nbsp;7&nbsp;)。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;然后有N个整数a[]，例如1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6&nbsp;7&nbsp;(&nbsp;N&nbsp;=&nbsp;7&nbsp;)。<BR>&nbsp;&nbsp;&nbsp;&nbsp;那么如何解密呢？TT强大地心理推测能力已经解决这个问题，解析密码需要一个“钥匙”k，知道k的值和密码后就可以解析了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;解析的方法如下：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;取出字符串S[1..k]，即字符串S的前k位，记为方式way（way应当是一个字符串）。（结果ans初始位a[k]）<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;然后执行下列操作：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.将指针p指向k<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.将指针p加一，如果超过N则结束运算。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.取出S[p-k+1..p]，即取出字符串S的第p-k+1位至第p位，将这个字符串与way比较，如果完全相同则继续操作，否则转2。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.如果a[p]大于max，那么更新max（max&nbsp;=&nbsp;a[p]）,转2。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;最后ans即为答案，简单地说ans&nbsp;=&nbsp;max{&nbsp;a[p]&nbsp;}&nbsp;（其中p满足S[1..k]&nbsp;=&nbsp;S[p-k+1..p]）<BR>&nbsp;&nbsp;&nbsp;&nbsp;ans的意义是一个重要参数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;为了得知ans，TT正在通过各种途径计算“钥匙”k，但是由于疏忽和割类错误（一种数据出现故意的失误），TT还在努力地收集一些修正信息，例如：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C&nbsp;1&nbsp;2&nbsp;&nbsp;&nbsp;（一般形式：C&nbsp;i&nbsp;t）<BR>&nbsp;&nbsp;&nbsp;&nbsp;其中的表示将a[1]修改为2（将a[i]修改为t），现在你要帮助TT计算ans和修改数值a[]。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行包括两个整数N,M，表示密码长度为N，有M条指令（询问或修改）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来一行包括一个长度为N的字符串，没有多余空格，仅包含小写字母。表示密码的第一部分。<BR>&nbsp;&nbsp;&nbsp;&nbsp;然后有N个整数，表示密码的第二部分a[]。<BR>&nbsp;&nbsp;&nbsp;&nbsp;最后有M行，每行是一条指令，指令要么是：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A&nbsp;k&nbsp;&nbsp;&nbsp;&nbsp;（询问，{k是整数}，计算“钥匙”为k时的重要参数ans的值。）<BR>&nbsp;&nbsp;&nbsp;&nbsp;要么是：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C&nbsp;i&nbsp;t&nbsp;&nbsp;（修改，{i,t都是整数）修改a[i]，使a[i]=t，注意这是永久修改）<BR>&nbsp;&nbsp;&nbsp;&nbsp;按顺序执行每一条指令即可。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;对于每一个询问指令，输出计算后的重要参数ans。<BR> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;30000&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;M&nbsp;&lt;=&nbsp;30000<BR>&nbsp;&nbsp;&nbsp;&nbsp;-10^9&nbsp;&lt;=&nbsp;a[j]&nbsp;,&nbsp;t&nbsp;&lt;=&nbsp;10^9&nbsp;（其中1&nbsp;&lt;=&nbsp;j&nbsp;&lt;=&nbsp;N）<BR>&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&lt;=&nbsp;k&nbsp;,&nbsp;i&nbsp;&lt;=&nbsp;N<BR>&nbsp;&nbsp;&nbsp;&nbsp;字符串中只会出现字母（包括大小写）、数字和‘@’、‘#’。<BR>&nbsp;&nbsp;&nbsp;&nbsp;星际战争系列，Guiolk联盟。<BR>&nbsp;&nbsp;&nbsp;&nbsp;EZ_gx原创。<BR> 
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
<tr><td>3 4
aba
1 2 3
A 1
C 3 4
A 1
A 2
</td><td>3
4
2</td></tr></table>
