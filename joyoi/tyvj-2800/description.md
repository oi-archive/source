# 

 
 # 题目描述 
<p>
写电子邮件是有趣的，但不幸的是经常写不好看，主要是因为所有的行不一样长，你的上司想要发排版精美的电子邮件，你的任务是为他编写一个电子邮件排版程序。<br>完成这个任务最简单的办法是在太短的行中的单词之间插入空格，但这并不是最好的方法，考虑如下例子：<br>****************************<br>This is the example you  are<br>actually considering.<br>假设我们想将第二行变得和第一行一样长，靠简单地插入空格则我们将得到如下结果：<br>****************************<br>This is the example you  are<br>actually        considering.<br><br>但这太难看了，因为在第二行中有一个非常大的空白，如果将第一行的单词“are”移到下一行我们将得到较好的结果：<br>****************************<br>This  is  the  example   you<br>are  actually   considering.<br><br>当然，这必须对难看程度进行量化。因此我们必须给出单词之间的空格的难看程度，一个包含N个空格符的空白段，其难看程度值为(n-1)2，程序的目的是使难看程度的总和最小化。例如，第一个例子的难看程度是1+7*7=50，而第二个例子的难看程度仅为1+1+1+4+1+4=12。<br>输出时，每一行的开头和结尾处都必须是一个单词，即每行开头和结尾处不能有空白。唯一例外的是该行仅有一个单词组成的情况，对于这种情况你可将单词放在该行开头处输出，此时如果该单词比该行应有的长度短则我们指定它的最坏程度为500，当然在这种情况下，该行的实际长度即为该单词的长度。<br><br></p> 

 
 # 输入格式 
<p>
输入文件第一行是一个整数N，表示该段要求达到的宽度，1<=N<=80。该段文章由一个或多个单词组成，单词由ASCII码值为33到126（包含33和126）的字符组成，单词与单词之间用空格隔开（可能超过一个）。单词长度不会超过段落要求达到的宽度。一段文字所有单词的总长度不会超过10000个字符，任何一行都不会超过100个字符，任何一个单词都在同一行内。</p> 

 
 # 输出格式 
<p>
对于每个段落，找出使其难看程度最小的排版形式并输出句子：<br>“Minimal badness is B.”(不包括引号和颜色),B是指按可能的最好排版形式会发生的难看程度值。注意排版后文本行数任意，多余的空格也可删除。<br></p> 

 
 # 提示 
<p>
样例解释:<br>This  is  the  example   you<br>are  actually   considering.<br>如上文所解释<br><br>数据规模：<br>对于100%的数据如题目描述.<br><br></p> 
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
<tr><td>28	
This is the example you  are
actually considering.
</td><td>Minimal badness is 12.</td></tr></table>
