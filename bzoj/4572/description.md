
# Description

<div class="content"><div>近日，谷歌研发的围棋AI—AlphaGo以4:1的比分战胜了曾经的世界冠军李世石，这是人工智能领域的又一里程碑。</div>
<div>与传统的搜索式AI不同，AlphaGo使用了最近十分流行的卷积神经网络模型。在卷积神经网络模型中，棋盘上每一</div>
<div>块特定大小的区域都被当做一个窗口。例如棋盘的大小为5×6，窗口大小为2×4，那么棋盘中共有12个窗口。此外</div>
<div>，模型中预先设定了一些模板，模板的大小与窗口的大小是一样的。下图展现了一个5×6的棋盘和两个2×4的模板</div>
<div>。对于一个模板，只要棋盘中有某个窗口与其完全匹配，我们称这个模板是被激活的，否则称这个模板没有被激活</div>
<div>。例如图中第一个模板就是被激活的，而第二个模板就是没有被激活的。我们要研究的问题是：对于给定的模板，</div>
<div>有多少个棋盘可以激活它。为了简化问题，我们抛开所有围棋的基本规则，只考虑一个n×m的棋盘，每个位置只能</div>
<div>是黑子、白子或无子三种情况，换句话说，这样的棋盘共有3n×m种。此外，我们会给出q个2×c的模板。我们希望</div>
<div>知道，对于每个模板，有多少种棋盘可以激活它。强调：模板一定是两行的。</div>
<div></div></div>

# Input

<div class="content"><div>输入数据的第一行包含四个正整数n，m，c和q，分别表示棋盘的行数、列数、模板的列数和模板的数量。随后2×q</div>
<div>行，每连续两行描述一个模板。其中，每行包含c个字符，字符一定是‘W’，‘B’或‘X’中的一个，表示白子、</div>
<div>黑子或无子三种情况的一种。N&lt;=100,M&lt;=12,C&lt;=6,Q&lt;=5</div></div>

# Output

<div class="content"><p> 输出应包含q行，每行一个整数，表示符合要求的棋盘数量。由于答案可能很大，你只需要输出答案对1,000,000,007取模后的结果即可。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 1 1 2 <br/>
B <br/>
W <br/>
B <br/>
B</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

