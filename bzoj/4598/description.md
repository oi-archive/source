
# Description

<div class="content"><div>给出n个结点的树结构T，其中每一个结点上有一个字符，这里我们所说的字符只考虑大写字母A到Z,再给出长度为m</div>
<div>的模式串s，其中每一位仍然是A到z的大写字母。Alice希望知道，有多少对结点&lt;u，v&gt;满足T上从u到V的最短路径</div>
<div>形成的字符串可以由模式串S重复若干次得到？这里结点对&lt;u，v&gt;是有序的，也就是说&lt;u，v&gt;和&lt;v，u&gt;需要被区分.</div>
<div>所谓模式串的重复，是将若干个模式串S依次相接（不能重叠).例如当S=PLUS的时候，重复两次会得到PLUSPLUS，</div>
<div>重复三次会得到PLUSPLUSPLUS,同时要注恿，重复必须是整数次的。例如当S=XYXY时，因为必须重复整数次，所以X</div>
<div>YXYXY不能看作是S重复若干次得到的。</div>
<div></div></div>

# Input

<div class="content"><div>每一个数据有多组测试，</div>
<div>第一行输入一个整数C，表示总的测试个数。</div>
<div>对于每一组测试来说：</div>
<div>第一行输入两个整数，分别表示树T的结点个数n与模式长度m。结点被依次编号为1到n，</div>
<div>之后一行，依次给出了n个大写字母（以一个长度为n的字符串的形式给出），依次对应树上每一个结点上的字符（</div>
<div>第i个字符对应了第i个结点).</div>
<div>之后n-1行，每行有两个整数u和v表示树上的一条无向边，之后一行给定一个长度为m的由大写字母组成的字符串，</div>
<div>为模式串S。</div>
<div>1&lt;=C&lt;=10,3&lt;=N&lt;=10000003&lt;=M&lt;=1000000</div>
<div style="font-size: 12.222222328186px;"></div></div>

# Output

<div class="content"><div>给出C行，对应C组测试。每一行输出一个整数，表示有多少对节点&lt;u,v&gt;满足从u到v的路径形成的字符串恰好是模</div>
<div>式串的若干次重复.</div>
<div></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
11 4<br/>
IODSSDSOIOI<br/>
1 2<br/>
2 3<br/>
3 4<br/>
1 5<br/>
5 6<br/>
6 7<br/>
3 8<br/>
8 9<br/>
6 10<br/>
10 11<br/>
SDOI </span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p> 数据文件太过巨大，仅提供前三组数据测试.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By AHdoc命题 鸣谢Loi_DQS上传">By AHdoc命题 鸣谢Loi_DQS上传</a></p></div>

