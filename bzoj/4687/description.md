
# Description

<div class="content"><div>Stylish 是一种编程语言，其语法包括名称（拉丁字母组成的序列）、三种分组符号、句号(‘.’)和换行符。分</div>
<div>组符号即圆括号(‘(’和‘)’)、大括号(‘{’和‘}’)和方括号(‘[’和‘]’)，它们必须正确地匹配和嵌套。</div>
<div>不同于大多数编程语言，Stylish 使用句号来分隔每个词，而不是使用空格，下图就是一个使用 Stylish 编程的</div>
<div>例子。</div>
<div><img src="/source/bzoj/4687/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC9mZi5wbmc=.png" width="566" height="200" alt=""/></div>
<div>正如你从上面的例子所看到的那样， Stylish 代码通过句号来缩进，每行的缩进量就是前导句号的数量。</div>
<div>你的任务是向一位 Stylish 编程大师学习他的缩进风格，并成为最年轻的 Stylish 编程大师。一种良好的 Styli</div>
<div>sh 缩进风格被定义为整数组成的三元组 (R,C,S)  ，其中 1≤R,C,S≤20 ，而 R,C,S 分别表示一个左圆括号、左</div>
<div>大括号、左方括号所带来的缩进量。在一个具有良好缩进风格的 Stylish 代码里，每一行的缩进量都应该是 R(r_</div>
<div>o-r_c )+C(c_o-c_c )+S(s_o-s_c )  ，其中 r_o,c_o,s_o  分别表示这一行之前的左圆括号、左大括号、左方括</div>
<div>号数量，r_c,c_c,s_c  分别表示这一行之前的右圆括号、右大括号、右方括号数量。因此第一行没有任何缩进量</div>
<div>。上面的例子可以被格式化为缩进风格 (R,C,S)=(9,5,2)  。由于第一行只有一个左圆括号，所以第二行的缩进量</div>
<div>是 9 ，同理第五行的缩进量是 7 。每个 Stylish 编程大师都有自己独特的缩进风格，并且写出的程序都是具有</div>
<div>良好缩进风格的，你需要写一个程序来模仿 Stylish 编程大师的缩进风格。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组测试数据。每组数据的第一行包含两个整数 p(1≤p≤10)  和 q(1≤q≤10)  。接下来 p 行是一位</div>
<div>编程大师具有良好缩进风格的代码，再接下来 q 行是一份完全没有缩进的代码。输入以两个零作为结束。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，则输出 q 行，表示模仿编程大师的代码风格后改写的那份完全没有缩进的代码每一行应该有的缩</div>
<div>进量，如果缩进量有多种可能则输出-1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
(Follow.my.style<br/>
.........starting.from.round.brackets)<br/>
{then.curly.brackets<br/>
.....[.and.finally<br/>
.......square.brackets.]}<br/>
(Thank.you<br/>
{for.showing.me<br/>
[all<br/>
the.secrets]})<br/>
4 2<br/>
(This.time.I.will.show.you<br/>
.........(how.to.use.round.brackets)<br/>
.........[but.not.about.square.brackets]<br/>
.........{nor.curly.brackets})<br/>
(I.learned<br/>
how.to.use.round.brackets)<br/>
4 2<br/>
(This.time.I.will.show.you<br/>
.........(how.to.use.round.brackets)<br/>
.........[but.not.about.square.brackets]<br/>
.........{nor.curly.brackets})<br/>
[I.have.not.learned<br/>
how.to.use.square.brackets]<br/>
2 2<br/>
(Be.smart.and.let.fear.of<br/>
..(closed.brackets).go)<br/>
(A.pair.of.round.brackets.enclosing<br/>
[A.line.enclosed.in.square.brackets])<br/>
1 2<br/>
Telling.you.nothing.but.you.can.make.it<br/>
[One.liner.(is).(never.indented)]<br/>
[One.liner.(is).(never.indented)]<br/>
2 4<br/>
([{Learn.from.my.KungFu<br/>
...}])<br/>
((<br/>
{{<br/>
[[<br/>
]]}}))<br/>
1 2<br/>
Do.not.waste.your.time.trying.to.read.from.emptiness<br/>
(<br/>
)<br/>
2 3<br/>
({Quite.interesting.art.of.ambiguity<br/>
....})<br/>
{<br/>
(<br/>
)}<br/>
2 4<br/>
({[<br/>
............................................................]})<br/>
(<br/>
{<br/>
[<br/>
]})<br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 9 14 16<br/>
0 9<br/>
0 -1<br/>
0 2<br/>
0 0<br/>
0 2 4 6<br/>
0 -1<br/>
0 -1 4<br/>
0 20 40 60<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

