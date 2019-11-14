# 

 
 # 题目描述 
<p>
文件压缩（ZIP.pas\c\cpp）<br><br>【题目描述】<br>　　提高文件的压缩率一直是人们追求的目标。近几年有人提出了这样一种算法，它虽然只是单纯地对文件进行重排，本身并不压缩文件，但是经这种算法调整后的文件在大多数情况下都能获得比原来更大的压缩率。<br>　　该算法具体如下：对一个长度为n的字符串S，首先根据它构造n个字符串，其中第i个字符串由将S的前i-1个字符置于末尾得到。然后把这n个字符串按照首字符从小到大排序，如果两个字符串的首字符相等，则按照它们在S中的位置从小到大排序。排序后的字符串的尾字符可以组成一个新的字符串S’，它的长度也是n，并且包含了S中的每一个字符。最后输出S’以及S的首字符在S’中的位置p。举例：<br>　　S:　example		<br>　　1、构造n个字符串<br>　　　　example<br>　　　　xamplee<br>　　　　ampleex<br>　　　　mpleexa<br>　　　　pleexam<br>　　　　leexamp<br>　　　　eexampl<br>　　2、将字符串排序<br>　　　　ampleex<br>　　　　example<br>　　　　eexampl<br>　　　　leexamp<br>　　　　mpleexa<br>　　　　pleexam<br>　　　　xamplee	<br>　　3、压缩结果<br>　　　　xelpame　　　　　S’<br>　　　　7　　　　　　　　p<br>　　由于英语单词构造的特殊性，某些字母对出现的频率很高，因此在S’中相同的字母有很大几率排在一起，从而提高S’的压缩率。　　虽然这种算法利用了英语单词的特性，然而在实践的过程中，人们发现它几乎适用于所有的文件压缩。<br>　　请你编一个程序，读入S’和p，输出字符串S。<br></p> 

 
 # 输入格式 
<p>
　　输入文件ZIP.IN共有三行，第1行是一个整数n（1<=n<=10000），代表S’的长度，第2行是字符串S’，第3行是整数p。</p> 

 
 # 输出格式 
<p>
　　输出文件ZIP.OUT仅包含一行S。</p> 
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
xelpame
7
</td><td>example</td></tr></table>
