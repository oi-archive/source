
# Description

<div class="content"><p>这些日子，可可不和卡卡一起玩了，原来可可正废寝忘食的想做一个简单而高效的文本编辑器。你能帮助他吗？为了明确任务目标，可可对“文本编辑器”做了一个抽象的定义： <img border="0" alt="" src="/source/bzoj/1269/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEyNjdfMS5qcGc=.jpg"/> <img border="0" alt="" src="/source/bzoj/1269/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEyNjdfMi5qcGc=.jpg"/> 文本：由0个或多个字符构成的序列。这些字符的ASCII码在闭区间[32, 126]内，也就是说，这些字符均为可见字符或空格。光标：在一段文本中用于指示位置的标记，可以位于文本的第一个字符之前，文本的最后一个字符之后或文本的某两个相邻字符之间。文本编辑器：为一个可以对一段文本和该文本中的一个光标进行如下七条操作的程序。如果这段文本为空，我们就说这个文本编辑器是空的。 编写一个程序： 建立一个空的文本编辑器。 从输入文件中读入一些操作指令并执行。 对所有执行过的GET操作，将指定的内容写入输出文件。</p></div>

# Input

<div class="content"><p>输入文件中第一行是指令条数N，以下是需要执行的N个操作。除了回车符之外，输入文件的所有字符的ASCII码都在闭区间[32, 126]内。且行尾没有空格。</p></div>

# Output

<div class="content"><p>依次对应输入文件中每条GET指令的输出，不得有任何多余的字符。</p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
Insert 13<br/>
Balanced eert<br/>
Move 2<br/>
Delete 5<br/>
Next<br/>
Insert 7<br/>
 editor<br/>
Move 0<br/>
Get<br/>
Move 11<br/>
Rotate 4<br/>
Get<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">B<br/>
t<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对输入数据我们有如下假定： MOVE操作不超过50 000个，INSERT、DELETE和ROTATE操作作的总个数不超过6 000，GET操作不超过20 000个，PREV和NEXT操作的总个数不超过20 000。 所有INSERT插入的字符数之和不超过2M（1M=1 024*1 024）。 DELETE操作、ROTATE操作和GET操作执行时光标后必然有足够的字符。MOVE、PREV、NEXT操作不会把光标移动到非法位置。 输入文件没有错误。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢seter重新制作数据">鸣谢seter重新制作数据</a></p></div>

