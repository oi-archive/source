
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">DFA（确定性有限状态自动机）是一个有向图，顶点称为状态，边称为转移。每个转移用一个字母标记。对于每个状态s和每个转移l，至多有一个转移从s出发且标记为l。DFA有一个初始状态和若干个结束状态。DFA定义的语言的单词可以由从开始状态到结束状态的路径上所有的字母连接起来。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">图中表示一个语言（包括单词：fix,foo,ox）的DFA。第一个DFA有7个状态，它不是最优的。第二个DFA定义的是同一个语言，但只有5个状态。</span></div>
<div><span style="font-size: medium">给定一个语言，包含有限个单词，求出定义该语言的DFA得最少状态数。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第一行有一个整数n(1&lt;=n&lt;=5000)，表示语言的单词数。接下来n行，每行一个单词。每个单词由1到30个小写字母组成。输入的所有单词互不相同。</span></div></div>

# Output

<div class="content"><div style="margin: 13pt 0cm"> </div>
<div><span style="font-size: medium">    一个数，定义该语言的DFA得最少状态数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
fix<br/>
foo<br/>
ox<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

