# 

 
 # 题目背景 
NOIP2009第一题<BR> 

 
 # 题目描述 
R&nbsp;国和S&nbsp;国正陷入战火之中，双方都互派间谍，<BR>潜入对方内部，伺机行动。<BR>历尽艰险后，潜伏于&nbsp;S&nbsp;国的R&nbsp;国间谍小C&nbsp;终于摸<BR>清了S&nbsp;国军用密码的编码规则：<BR>1．&nbsp;S&nbsp;国军方内部欲发送的原信息经过加密后在网<BR>络上发送，原信息的内容与加密后所<BR>得的内容均由大写字母‘A’-‘Z’构成（无空格等其他<BR>字符）。<BR>2．&nbsp;S&nbsp;国对于每个字母规定了对应的“密字”。加密<BR>的过程就是将原信息中的所有字母替<BR>换为其对应的“密字”。<BR>3．&nbsp;每个字母只对应一个唯一的“密字”，不同的字<BR>母对应不同的“密字”。“密字”可以<BR>和原字母相同。<BR>例如，若规定‘A’的密字为‘A’，‘B’的密字为‘C’（其<BR>他字母及密字略），则原信<BR>息“ABA”被加密为“ACA”。<BR>现在，小&nbsp;C&nbsp;通过内线掌握了S&nbsp;国网络上发送的一<BR>条加密信息及其对应的原信息。小C<BR>希望能通过这条信息，破译S&nbsp;国的军用密码。小C&nbsp;<BR>的破译过程是这样的：扫描原信息，对<BR>于原信息中的字母x（代表任一大写字母），找到<BR>其在加密信息中的对应大写字母y，并认为<BR>在密码里y&nbsp;是x&nbsp;的密字。如此进行下去直到停止于<BR>如下的某个状态：<BR>1．&nbsp;所有信息扫描完毕，‘A’-‘Z’&nbsp;所有&nbsp;26&nbsp;个字母在<BR>原信息中均出现过并获得了相应<BR>的“密字”。<BR>2．&nbsp;所有信息扫描完毕，但发现存在某个（或某<BR>些）字母在原信息中没有出现。<BR>3．&nbsp;扫描中发现掌握的信息里有明显的自相矛盾<BR>或错误（违反S&nbsp;国密码的编码规则）。例<BR>如某条信息“XYZ”被翻译为“ABA”就违反了“不同字<BR>母对应不同密字”的规则。<BR>在小&nbsp;C&nbsp;忙得头昏脑涨之际，R&nbsp;国司令部又发来电<BR>报，要求他翻译另外一条从S&nbsp;国刚刚<BR>截取到的加密信息。现在请你帮助小C：通过内线<BR>掌握的信息，尝试破译密码。然后利用破<BR>译的密码，翻译电报中的加密信息。<BR> 

 
 # 输入格式 
输入共3&nbsp;行，每行为一个长度在1&nbsp;到100&nbsp;之<BR>间的字符串。<BR>第&nbsp;1&nbsp;行为小C&nbsp;掌握的一条加密信息。<BR>第&nbsp;2&nbsp;行为第1&nbsp;行的加密信息所对应的原信息<BR>。<BR>第&nbsp;3&nbsp;行为R&nbsp;国司令部要求小C&nbsp;翻译的加密信<BR>息。<BR>输入数据保证所有字符串仅由大写字母‘A’<BR>-‘Z’构成，且第1&nbsp;行长度与第2&nbsp;行相等。<BR> 

 
 # 输出格式 
输出共1&nbsp;行。<BR>若破译密码停止时出现&nbsp;2，3&nbsp;两种情况，请<BR>你输出“Failed”（不含引号，注意首字母<BR>大<BR>写，其它小写）。<BR>否则请输出利用密码翻译电报中加密信息后<BR>得到的原信息。<BR> 

 
 # 提示 
【输入输出样例说明】<BR>原信息中的字母‘A’和‘B’对<BR>应相同的密字，输出“Failed”<BR> 
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
<tr><td>AA
AB
EOWIE
</td><td>Failed
</td></tr></table>
