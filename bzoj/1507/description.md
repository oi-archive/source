
# Description

<div class="content"><div>很久很久以前，DOS3.x的程序员们开始对 EDLINEDLIN 感到厌倦。</div>
<div>于是，人们开始纷纷改用自己写的文本编辑器??</div>
<div>多年之后，出于偶然的机会，小明找到了当时的一个编辑软件。进行了一些简单的测试后，</div>
<div>小明惊奇地发现：那个软件每秒能够进行上万次编辑操作（当然，你不能手工进行这样的测试） ！</div>
<div>于是，小明废寝忘食地想做一个同样的东西出来。你能帮助他吗？</div>
<div>为了明确目标，小明对“文本编辑器”做了一个抽象的定义:</div>
<div>文本：由 0 个或多个 ASCII 码在闭区间[3232 , 126126 ]内的字符构成的序列。</div>
<div>光标：在一段文本中用于指示位置的标记，可以位于文本首部，文本尾部或文本的某两个字符之间。</div>
<div>文本编辑器：由一段文本和该文本中的一个光标组成的，支持如下操作的数据结构。</div>
<div>如果这段文本为空，我们就说这个文本编辑器是空的。</div>
<div>操作名称<span class="Apple-tab-span" style="white-space:pre">	</span>输入文件中的格式     功能</div>
<div>MOVE(k)<span class="Apple-tab-span" style="white-space:pre">	</span>        Move k             将光标移动到第 k个字符之后，如果 k=0，将光标移到文本开头</div>
<div>INSERT(n,s)<span class="Apple-tab-span" style="white-space:pre">	</span>Insert n s         在光标处插入长度为n的字符串s，光标位置不变n≥1</div>
<div>DELETE(n)<span class="Apple-tab-span" style="white-space:pre">	</span>Delete n           删除光标后的n个字符，光标位置不变，n ≥ 1</div>
<div>GET(n)<span class="Apple-tab-span" style="white-space:pre">	</span>        Get n               输出光标后的n个字符，光标位置不变，n ≥ 1</div>
<div>PREV()<span class="Apple-tab-span" style="white-space:pre">	</span>        Prev<span class="Apple-tab-span" style="white-space:pre">	</span>                光标前移一个字符</div>
<div>NEXT()<span class="Apple-tab-span" style="white-space:pre">	</span>        Next<span class="Apple-tab-span" style="white-space:pre">	</span>                光标后移一个字符</div>
<div>你的任务是：</div>
<div>建立一个空的文本编辑器。</div>
<div>从输入文件中读入一些操作并执行。</div>
<div>对所有执行过的 GET 操作，将指定的内容写入输出文件。</div></div>

# Input

<div class="content"><div>第一行是指令条数t，以下是需要执行的t个操作。</div>
<div>其中： 为了使输入文件便于阅读，Insert操作的字符串中可能会插入一些回车符，</div>
<div>请忽略掉它们（如果难以理解这句话，可以参考样例）。 </div>
<div>除了回车符之外，输入文件的所有字符的ASCII码都在闭区间[32, 126]内。且行尾没有空格。 </div>
<div>这里我们有如下假定： </div>
<div>MOVE操作不超过50000个</div>
<div>INSERT和DELETE操作的总个数不超过4000</div>
<div>PREV和NEXT操作的总个数不超过200000。 <span class="Apple-tab-span" style="white-space:pre">	</span></div>
<div>所有INSERT插入的字符数之和不超过2M（1M=1024*1024）</div>
<div>正确的输出文件长度不超过3M字节。 <span class="Apple-tab-span" style="white-space:pre">	</span></div>
<div>DELETE操作和GET操作执行时光标后必然有足够的字符。</div>
<div>MOVE、PREV、NEXT操作必然不会试图把光标移动到非法位置。 <span class="Apple-tab-span" style="white-space:pre">	</span></div>
<div>输入文件没有错误。 </div>
<div>对C++选手的提示：经测试，最大的测试数据使用fstream进行输入有可能会比使用stdio慢约1秒。</div></div>

# Output

<div class="content"><p>每行依次对应输入文件中每条GET指令的输出。</p></div>

# Sample Input

<div class="content"><span class="sampledata">15<br/>
Insert 26<br/>
abcdefghijklmnop<br/>
qrstuv wxy<br/>
Move 15<br/>
Delete 11<br/>
Move 5<br/>
Insert 1<br/>
^<br/>
Next<br/>
Insert 1<br/>
_<br/>
Next<br/>
Next<br/>
Insert 4<br/>
.\/.<br/>
Get 4<br/>
Prev<br/>
Insert 1<br/>
^<br/>
Move 0<br/>
Get 22<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">.\/.<br/>
abcde^_^f.\/.ghijklmno<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

