<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小Q手中有一棵二叉树，它有n个节点，编号1至n。现在，小Q给你出了一道难题，题目是让你将这些节点依次删除，并规定你只能删除没有父亲的节点（即删除一个节点前，必须将其祖先全部删除）。而游戏的难点在于，你并不知道这棵树的形态，只能通过以下方式向小Q询问，而小Q也会诚实地告诉你答案：<br/>
　　询问方式：p号点和q号点的祖先关系。<br/>
　　回答有三种：p是q的祖先；q是p的祖先；以上皆非。<br/>
　　其中，祖先的定义为：一个点A到根的简单路径上的所有点（不含A）都是A的祖先。<br/>
　　你需要做的，就是通过尽可能少的询问将所有点全部删除。</div>
# 规则介绍

<div class="pdcont">　　这是一道交互类型题目，要求选手使用C++语言进行编程。在程序开头，我们已经为你声明了四个函数供你使用，他们分别是：<br/>
　　int size()  //返回这棵树的节点数量n<br/>
　　int type()  //返回这棵树的类型（1、2、3，在数据规模中有详细介绍）<br/>
　　int question(int p, int q) //返回p号点和q号点的关系，若返回值为1，表示p是q的祖先，若返回值为-1，表示q是p的祖先，否则返回值为0，特别注意p和q必须为1至n的整数<br/>
　　void submit(x)  //删除x号节点，特别注意x必须为1至n的整数<br/>
<br/>
　　对于前三个函数，你的程序可以调用任意次。而对于第四个函数，你的程序只能调用n次，且每个节点必须恰好被删除一次。并且，你的程序要保证每次删除的节点均为没有父亲的节点。<br/>
　　若你的程序满足上述要求并在规定时间内正常结束，系统会统计你的程序使用question(int p, int q)函数的次数记作yournum，并与我们提供的五个评分参数a1&gt;=a2&gt;=a3&gt;=a4&gt;=a5作比较。若yournum &lt;= ai，则你的得分为i分，同时满足多个取最高得分。<br/>
　　提示：经测试，question()函数每秒钟大约可调用2*10^8次。计算时间复杂度时请考虑此因素。<br/>
　　特别地，你的程序<b>不允许</b>进行任何输入输出操作，否则将按<b>0分</b>处理。</div>
# 样例程序

<div class="pdcont">　　using namespace std;<br/>
　　int main()<br/>
　　{<br/>
　　if (size() == 2) //若n=2，以下算法可以通过一次询问保证正确性<br/>
　　{<br/>
　　if (question(1, 2) == 1) //询问1和2的祖先关系<br/>
　　{//若1是2的祖先，则先删1再删2<br/>
　　submit(1);<br/>
　　submit(2);<br/>
　　}<br/>
　　else<br/>
　　{//否则先删2再删1<br/>
　　submit(2);<br/>
　　submit(1);<br/>
　　}<br/>
　　}<br/>
　　else //若n不为2，则按1~n的顺序删，当然这就不能保证正确性了<br/>
　　for (int i=1; i&lt;=size(); i++)<br/>
　　submit(i);<br/>
　　}</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">n<br/>
</td><td valign="top" style="border:solid 1.0pt">数据类型<br/>
</td><td valign="top" style="border:solid 1.0pt">所占比例<br/>
</td><td valign="top" style="border:solid 1.0pt">n<br/>
</td><td valign="top" style="border:solid 1.0pt">数据类型<br/>
</td><td valign="top" style="border:solid 1.0pt">所占比例<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">&lt;=5000<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">10%<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=300000<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">10%<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">&lt;=5000<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">10%<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=300000<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">20%<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">&lt;=5000<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">25%<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">25%<br/>
</td></tr></tbody></table>　　数据规模即int size()的返回值，表示这棵树的节点数量。<br/>
　　数据类型即int type()的返回值：<br/>
　　1表示这棵树为一个“链”，准确地说每个点最多只有一个儿子；<br/>
　　2表示这棵树为一棵满二叉树；<br/>
　　3表示我们不知道这棵树有什么特殊形态。</div>

</div>