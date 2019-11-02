# 

 
 # 题目背景 
<p>Moe-ing与Psyaomo123联合出题</p> 

 
 # 题目描述 
<p>dota是一款非常流行的著名游戏，Moe-ing与Psyaomo123最近也迷上了dota。<br />
有一次Moe-ing与Psyaomo123一起玩dota，由于我方gank（gank指突袭&nbsp;并且杀掉对手）不力，使对方的英雄发育良好，所以Psyaomo123让Moe-ing去gank对方的英雄，由于对方有人开了外挂（-&nbsp;-B汗），可以看到我们的聊天记录，所以Psyaomo123发明了一种密码，破译出后是要gank的对方英雄的名字。这套密码是这样的：给出一个数n，表示那个英雄的名字有几个字母；然后n行是n个字符串，每个字符串中包含了一个要gank的敌方英雄的名字中的字母，由于字符串杂乱无章，所以要按字典序排序。。。然后n行是n个正整数a[i]，第i个数字表示排序后第i个字符串中第a[i]位是英雄名字的第i位（有点绕）。还有一个数字m，表示是顺序还是倒序。。Moe-ing已经绕晕了，请你帮助他破译这个密码。</p> 

 
 # 输入格式 
<p>第一行两个正整数n，m&nbsp;n表示字符串个数（敌方英雄名字中字母个数）<br />
m为1或2&nbsp;m=1表示按字典顺序排，m=2表示按字典倒序排；<br />
第2到n+1行&nbsp;每行一个字符串，表示含有敌方英雄名字字母的密码；<br />
第n+2到2n+2行&nbsp;每行一个正整数，表示排序后字符串中第几位是英雄名字的字母；</p> 

 
 # 输出格式 
<p>一个字符串&nbsp;表示要gank的敌方英雄的名字；</p> 

 
 # 提示 
<p>由于敌方有崇洋媚外的玩家-&nbsp;-所以名字可能很长<br />
若排序后第i个字符串长度小于第i个数字&nbsp;就不输出<br />
n&lt;=100000&nbsp;&nbsp;每个输入字符串长度&lt;=255(输出数据不保证）Moe-ing与Psyaomo123联合出题</p> 
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
<tr><td>9 1
vijosser
wodotaer
moeing
psyaomo
ever
abcdefgn
iereplays
ehome
knever
8
1
2
4
6
1
5
8
7
</td><td>nevermore
注：排序后的顺序为
abcdefgn
ehome
ever
iereplays
knever
moeing
psyaomo
vijosser
wodotaer</td></tr></table>
