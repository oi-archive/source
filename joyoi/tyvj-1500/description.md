# 

 
 # 题目背景 
<p>广州市2011年市选第二试</p> 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;大家对GIF这种图形格式一定不陌生，现在我们用字符串压缩来解释GIF压缩图形的基本原理。<br />
&nbsp;&nbsp;&nbsp;&nbsp;GIF压缩的基础是一个数字编码与字符串映射关系的字典。字典只包含可能出现在待压缩字符串中的字符或子串的映射关系，且数字编码长度相同。例如，假如要压缩的字符串可能包含所有26个大写字母，那么字典可初始化为（A,00），（B,01），（C,02），&hellip;，（Z,25），注意数字编码长度都是2。假如我们只是想压缩DNA序列，那么字典可初始化为（A,0），（T,1），（G,2），（C,3）。<br />
&nbsp;&nbsp;&nbsp;&nbsp;压缩算法如下：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.在字典中查找字串未压缩部分最长的前缀，将这个前缀替换成字典对应的数字编码。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.如果字串尚有未完成压缩的部分，则在字典中添加一个映射关系（s,n），s是上一步骤找到的前缀加紧接其后的字符，n是字典中尚未使用的最小的编码。<br />
&nbsp;&nbsp;&nbsp;&nbsp;我们以压缩字符串ABABBAABB为例说明，由于字串只包含A和B，字典初始只有两项（A,0）和（B,1）。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;待压缩字串&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;最长前缀&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;替换成编码&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;新增字典条目<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ABABBAABB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(AB,2)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0BABBAABB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(BA,3)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;01ABBAABB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(ABB,4)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;012BAABB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(BAA,5)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0123ABB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ABB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;---<br />
&nbsp;&nbsp;&nbsp;&nbsp;最终的压缩结果是01234。<br />
&nbsp;&nbsp;&nbsp;&nbsp;还有一点要特别注意，当字典中不断添加新的映射关系，数字编码长度在某个步骤将突破初始化时的长度。由于字典所有数字编码长度要保持一致，这时要将字典中原有的数字编码前补0，之后的压缩按新的数字编码进行替换，而原有已替换的数字编码则不受影响。例如，ABABBAABBAABAABAB将压缩成01234027301，而不是<a href="tel:0123402731">0123402731</a>。<br />
&nbsp;&nbsp;&nbsp;&nbsp;请对输入的初始字典和压缩后的编码进行解压。</p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;第一行的字符串是压缩后的数字编码。第二行是初始的字典，由一个正整数n开始，n(1&lt;=n&lt;=100)是字典初始的条目数，后面接着n个字符串，字典中的第一个字符串编码为0（如n&gt;10则是00），第二个字符串编码为1，以此类推。</p> 

 
 # 输出格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;输出只有一行，是解压后的字符串。我们保证所有输入都是可以解压的。</p> 
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
<tr><td>(第1个)
01234
2 A B
(第2个)
01234027301
2 A B
(第3个)
21104
3 BA A C
(第4个)
01
2 JA VA
</td><td>(第1个)
ABABBAABB
(第2个)
ABABBAABBAABAABAB
(第3个)
CAABAAA
(第4个)
JAVA
</td></tr></table>
