# 

 
 # 题目描述 
很久很久以前，DOS3.x的程序员们开始对EDLIN感到厌倦。于是，人们开始纷纷改用自己写的文本编辑器……<BR>多年之后，出于偶然的机会，小明找到了当时的一个编辑软件。进行了一些简单的测试后，小明惊奇地发现：那个软件每秒能够进行上万次编辑操作（当然，你不能手工进行这样的测试）！于是，小明废寝忘食地想做一个同样的东西出来。你能帮助他吗？<BR>&nbsp;<BR>为了明确任务目标，小明对“文本编辑器”做了一个抽象的定义：<BR>文本：由0个或多个字符构成的序列。这些字符的ASCII码在闭区间[32,&nbsp;126]内，也就是说，这些字符均为可见字符或空格。<BR>光标：在一段文本中用于指示位置的标记，可以位于文本的第一个字符之前，文本的最后一个字符之后或文本的某两个相邻字符之间。<BR>文本编辑器：为一个可以对一段文本和该文本中的一个光标进行如下六条操作的程序。如果这段文本为空，我们就说这个文本编辑器是空的。<BR><BR>操作名称：MOVE(k)	输入文件中的格式：Move&nbsp;k	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;功能：将光标移动到第k个字符之后，如果k=0，将光标移到文本第一个字符之前<BR>操作名称：INSERT(n,&nbsp;s)	输入文件中的格式：Insert&nbsp;n[Enter]S	功能：在光标后插入长度为n的字符串s，光标位置不变，n&nbsp;&gt;=&nbsp;1<BR>操作名称：DELETE(n)	输入文件中的格式：Delete&nbsp;n	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;功能：删除光标后的n个字符，光标位置不变，n&nbsp;&gt;=&nbsp;1<BR>操作名称：GET(n)	输入文件中的格式：Get&nbsp;n	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;功能：输出光标后的n个字符，光标位置不变，n&nbsp;&gt;=&nbsp;1<BR>操作名称：PREV()	输入文件中的格式：Prev	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;功能：光标前移一个字符<BR>操作名称：NEXT()	输入文件中的格式：Next	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;功能：光标后移一个字符<BR><BR>你的任务是：<BR>建立一个空的文本编辑器。<BR>从输入文件中读入一些操作指令并执行。<BR>对所有执行过的GET操作，将指定的内容写入输出文件。<BR> 

 
 # 输入格式 
输入文件editor.in的第一行是指令条数t，以下是需要执行的t个操作。其中：<BR>为了使输入文件便于阅读，Insert操作的字符串中可能会插入一些回车符，请忽略掉它们（如果难以理解这句话，可以参考样例）。<BR>除了回车符之外，输入文件的所有字符的ASCII码都在闭区间[32,&nbsp;126]内。且行尾没有空格。<BR>&nbsp;<BR>这里我们有如下假定：<BR>MOVE操作不超过50000个，INSERT和DELETE操作的总个数不超过4000，PREV和NEXT操作的总个数不超过200000。<BR>所有INSERT插入的字符数之和不超过2M（1M=1024*1024），正确的输出文件长度不超过3M字节。<BR>DELETE操作和GET操作执行时光标后必然有足够的字符。MOVE、PREV、NEXT操作不会把光标移动到非法位置。<BR>输入文件没有错误。<BR> 

 
 # 输出格式 
输出文件editor.out的每行依次对应输入文件中每条GET指令的输出。<BR> 

 
 # 提示 
对C++选手的提示：经测试，对最大的测试数据使用fstream进行输入有可能会比使用stdio慢约1秒，因此建议在可以的情况下使用后者。<BR>NOI2003day1<BR><BR> 
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
<tr><td>15
Insert 26
abcdefghijklmnop
qrstuv wxy
Move 15
Delete 11
Move 5
Insert 1
^
Next
Insert 1
_
Next
Next
Insert 4
.\/.
Get 4
Prev
Insert 1
^
Move 0
Get 22
</td><td>.\/.
abcde^_^f.\/.ghijklmno
</td></tr></table>
