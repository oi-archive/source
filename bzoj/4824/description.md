
# Description

<div class="content"><div>老 C 是个程序员。    </div>
<div>作为一个优秀的程序员,老 C 拥有一个别具一格的键盘,据说这样可以大幅提升写程序的速度,还能让写出来的程序</div>
<div>在某种神奇力量的驱使之下跑得非常快。小 Q 也是一个程序员。有一天他悄悄潜入了老 C 的家中,想要看看这个</div>
<div>键盘究竟有何妙处。他发现,这个键盘共有n个按键,这n个按键虽然整齐的排成一列,但是每个键的高度却互不相同</div>
<div>。聪明的小 Q 马上将每个键的高度用 1 ~ n 的整数表示了出来,得到一个 1 ~ n 的排列 h1, h2,..., hn 。为了</div>
<div>回去之后可以仿造一个新键盘(新键盘每个键的高度也是一个 1 ~ n 的排列),又不要和老 C 的键盘完全一样,小 Q</div>
<div> 决定记录下若干对按键的高度关系。作为一个程序员,小 Q 当然不会随便选几对就记下来,而是选了非常有规律的</div>
<div>一些按键对:对于 i =2,3, ... , n,小 Q 都记录下了一个字符&lt;或者&gt;,表示 h_[i/2] &lt; h_i 或者h _[i/2] &gt; h_i </div>
<div>。于是,小 Q 得到了一个长度为n ? 1的字符串,开开心心的回家了。现在,小 Q 想知道满足他所记录的高度关系的</div>
<div>键盘有多少个。虽然小 Q 不希望自己的键盘和老 C 的完全相同,但是完全相同也算一个满足要求的键盘。答案可</div>
<div>能很大,你只需要告诉小 Q 答案 mod 1,000,000,007 之后的结果即可。</div>
<div></div></div>

# Input

<div class="content"><div>输入共 1 行,包含一个正整数 n 和一个长度为 n ? 1 的只包含&lt;和&gt;的字符串,分别表示键</div>
<div>盘上按键的数量,和小 Q 记录的信息,整数和字符串之间有一个空格间隔。</div>
<div></div></div>

# Output

<div class="content"><div>输出共 1 行,包含一个整数,表示答案 mod 1,000,000,007后的结果。    </div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 &lt;&gt;&gt;&lt;</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
共5个按键,第1个按键比第2个按键矮,第1个按键比第3个按键高,第2个按键比第4个<br/>
按键高,第2个按键比第5个按键矮。    <br/>
这5个按键的高度排列可以是 2,4,1,3,5 , 3,4,1,2,5 , 3,4,2,1,5 。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

