<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>中学数学里集合的元素往往是具体的数字，比如A = {1,2,3}，B = {}（空集）等等。但是要特别注意，集合的元素也可以是另一个集合，比如说C = {{}}，即说明C有且仅有一个元素——空集B，所以称B是C的子集或者称B是C的元素都是正确的。所谓一个集合的势，就是这个集合的元素个数，一般记为|S|，空集的势为0。在上例中，|A| = 3，|B| = 0，|C| = 1。</p>
<p>鉴于集合论是现代数学的基础理论这一事实，一群异想天开的科学家开始着手建造一台新式的超级计算机——集合堆栈机Alpha，这台机器操作的将是集合而不是数字。不过由于Alpha的竣工之日遥遥无期，科学家们希望你为他们编写一台虚拟机，好让他们检查自己的原型设计是否合理。</p>
<p>Alpha的存储设备只有一个栈，栈的每个单元都只能放置一个集合。一开始，栈是空的，在每个操作结束后，计算机就会输出位于栈顶单元的那个集合的势。Alpha拥有五种不同的指令，分别为：PUSH、DUP、UNION、INTERSECT和ADD，他们的功能如下：</p>
<p> </p>
<table border="0" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top" width="108">
<p>PUSH：</p>
</td>
<td valign="top" width="468">
<p>把一个空集{}压入栈；</p>
</td>
</tr>
<tr>
<td valign="top" width="108">
<p>DUP：</p>
</td>
<td valign="top" width="468">
<p>取出位于栈顶单元的集合，复制一遍以后再把两个同样的集合压入栈；</p>
</td>
</tr>
<tr>
<td valign="top" width="108">
<p>UNION：</p>
</td>
<td valign="top" width="468">
<p>取出位于栈顶单元的前两个集合，然后把它们的并集压入栈；</p>
</td>
</tr>
<tr>
<td valign="top" width="108">
<p>INTERSECT：</p>
</td>
<td valign="top" width="468">
<p>取出位于栈顶单元的前两个集合，然后把它们的交集压入栈；</p>
</td>
</tr>
<tr>
<td valign="top" width="108">
<p>ADD：</p>
</td>
<td valign="top" width="468">
<p>取出位于栈顶单元的前两个集合，首先取出的记为<em>S</em>，其次取出的记为<em>T</em>，最后把<em>T</em>∪{<em>S</em>}压入栈；</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p> </p>
<p> </p>
<p>以左图为例，可见位于虚拟机堆栈顶端的两个元素是：</p>
<p><em>A </em>= { {}, {{}} }</p>
<p><em>B </em>= { {}, {{{}}} }</p>
<p>根据势的定义，我们有|<em>A</em>| = 2 以及 |<em>B</em>|<em> </em>= 2。接下来，</p>
<p>l  如果选择UNION操作，结果是{{},{{}},{{{}}}，输出3</p>
<p>l  如果选择INTERSECT操作，结果是{{}}，输出1</p>
<p>l  如果选择ADD操作，结果是{{},{{{}}},{{},{{}}}}，输出3</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第一行只有一个整数n（0≤n≤2000），代表将要执行的指令条数。接下来有n行，每行有包含一条大写的指令，我们保证每条指令都是上述五条指令中的一条，并且虚拟机总是能正确执行完所有的指令。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出虚拟机的输出结果即可。每行输出一个大于或等于0的整数，代表虚拟机执行该条指令后的输出。选手们务必仔细考量程序的执行效率。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9</p>
<p>PUSH</p>
<p>DUP</p>
<p>ADD</p>
<p>PUSH</p>
<p>ADD</p>
<p>DUP</p>
<p>ADD</p>
<p>DUP</p>
<p>UNION</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>
<p>0</p>
<p>1</p>
<p>0</p>
<p>1</p>
<p>1</p>
<p>2</p>
<p>2</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，n ≤ 10。</p>
<p>对于100%的数据，n ≤ 2000。</p>
</div>
</div>