# 

 
 # 题目背景 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&ldquo;彭！&rdquo;我来到了天堂、地狱和人间的交界处，要好多生物在交谈！（好像只有5个-&nbsp;-!）</p> 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;这5个生物，编号为A~E，每个生物都有一个身份，人类(human)、天使(divine)或恶魔(evil)，天使永远说真话，恶魔永远说假话，人类白天说真话，晚上说假话。我完全无法分清他们的身份，现在请你根据他们的对话告诉我，哪些生物是天使，哪些生物是人类，哪些生物是恶魔，现在是白天还是晚上。</p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;第一行是一个正整数n。（1&le;n&le;100）<br />
&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，是这些生物的对话，这些对话都是以下三个句子之一：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&middot;T:&nbsp;X&nbsp;is&nbsp;[not]&nbsp;(divine|human|evil|lying).<br />
&nbsp;&nbsp;&nbsp;&nbsp;&middot;T:&nbsp;I&nbsp;am&nbsp;[not]&nbsp;(divine|human|evil|lying).<br />
&nbsp;&nbsp;&nbsp;&nbsp;&middot;T:&nbsp;It&nbsp;is&nbsp;(day|night).<br />
&nbsp;&nbsp;&nbsp;&nbsp;方括号中的词可以出现也可以不出现，圆括号中由|分隔的词必须出现一个。T是说话者的编号，X是被说者的编号。句子中没有多余的空格。</p> 

 
 # 输出格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;如果根据规则不可能有这样的对话，输出&ldquo;This&nbsp;is&nbsp;impossible.&rdquo;。<br />
&nbsp;&nbsp;&nbsp;&nbsp;否则先按照编号顺序，如果可以确定X的身份，输出&ldquo;X&nbsp;is&nbsp;(divine|evil|human).&rdquo;，如果不能确定X的身份，输出&ldquo;I&nbsp;don&#39;t&nbsp;know&nbsp;who&nbsp;X&nbsp;is.&rdquo;。（X为编号）最后如果可以确定是白天还是晚上，就输出&ldquo;It&nbsp;is&nbsp;(day|night).&rdquo;，如果不能确定是白天还是晚上，输出&ldquo;I&nbsp;don&#39;t&nbsp;know&nbsp;it&nbsp;is&nbsp;day&nbsp;or&nbsp;night.&rdquo;。<br />
&nbsp;&nbsp;&nbsp;&nbsp;输出时不要有多余空格，行末不要有多余的回车。</p> 

 
 # 提示 
<p>提示：<br />
&nbsp;&nbsp;&nbsp;&nbsp;第一个样例中，A显然在说谎，因为他说的话前后矛盾。B既不是魔鬼也不是人类，所以B一定是天使。<br />
&nbsp;&nbsp;&nbsp;&nbsp;第二个样例中，E说的话前后矛盾。所以C和D是天使。A和B的身份不确定。<br />
EZ_lzh</p> 
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
<tr><td>【样例输入1】
3
A: B is evil.
A: B is human.
B: A is evil.
【样例输入2】
6
A: B is lying.
B: A is lying.
C: D is divine.
D: C is divine.
E: D is evil.
E: D is human.
【样例输入3】
1
A: I am evil.
</td><td>【样例输出1】
A is evil.
B is divine.
I don't know it is day or night.
【样例输出2】
I don't know who A is.
I don't know who B is.
C is divine.
D is divine.
I don't know who E is.
I don't know it is day or night.
【样例输出3】
A is human.
It is night.
</td></tr></table>
