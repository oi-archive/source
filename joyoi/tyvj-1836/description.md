# 

 
 # 题目背景 
JSOI&nbsp;2009第一试第二题 

 
 # 题目描述 
众所周知，密码在信息领域起到了不可估量的作用。对于普通的登陆口令以，唯一的破解方法就是暴力破解——逐个尝试所有可能的字母组合，但这是一项很耗时又容易被发现的工作。所以，为了获取对方的登陆口令，在暴力破解密码之前，必须先做大量的准备工作。经过情报的搜集，现在得到了若干有用信息，形如：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“我观察到，密码中含有字符串***。”<BR>例如，对于一个10位的密码以及观察到的字符串hello与world,可能的密码组合为helloworld与worldhello;而对于6位的密码以及到的字符串good与day,可能的密码组合为gooday。<BR>有了这些信息，就能够大大地减少尝试的次数了。请编一个程序，计算所有密码组合的可能。密码中仅可能包含a-z之间的小写字母。 

 
 # 输入格式 
输入数据首先输入两个整数L,N，分别表示密码的长度与观察到子串的个数。<BR>接下来N行，每行若干个字符，描述了每个观察到的字符串。 

 
 # 输出格式 
输出数据第一行为一个整数，代表了满足所有观察条件字符串的总数。<BR>若这个数字小于等于42，则按字典顺序输出所有密码的可能情况，每行一个，否则，只输出满足所有观察条件字符串的总数即可。 

 
 # 提示 
数据规模&nbsp;对于100%的数据，1&lt;=L&lt;=25,1&lt;=N&lt;=10,每个观察到的字符串长不超过10，并且保证输出结果小于2^63。 
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
<tr><td>10 2
hello
world</td><td>2
helloworld
worldhello
</td></tr></table>
