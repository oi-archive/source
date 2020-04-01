
# Description

<div class="content"><p></p>
<p>某天，wangxz神犇来到了一个信息学在线评测系统(Online Judge)。由于他是一位哲♂学的神犇，所以他不打算做题。他发现这些题</p>
<p>目呈线性排列，被标记为1~n号，每道题都有一个难度值(可以&lt;=0)。他决定与这些题目玩♂耍。</p>
<p>1、他可以在某个位置插♂入一些难度值特定的题目。</p>
<p>2、他可以吃♂掉(删除)一段题目。</p>
<p>3、他可以查询某个位置的题目的难度值。</p>
<p>维护一个初始有n个元素的序列(标记为1~n号元素)，支持以下操作：</p>
<p>0 p a b (0&lt;=p&lt;=当前序列元素个数) (a&lt;=b) 在p位置和p+1位置之间插入整数:a,a+1,a+2,...,b-1,b。若p为0，插在序列最前面;</p>
<p>1 a b (1&lt;=a&lt;=b&lt;=当前序列元素个数) 删除a,a+1,a+2,...,b-1,b位置的元素;</p>
<p>2 p (1&lt;=p&lt;=当前序列元素个数) 查询p位置的元素。</p>
<p></p></div>

# Input

<div class="content"><p>输入第一行包括两个正整数n(1&lt;=n&lt;=20000),m(1&lt;=m&lt;=20000),代表初始序列元素个数和操作个数。</p>
<p>接下来n个整数,为初始序列元素。</p>
<p>接下来m行,每行第一个为整数sym,</p>
<p>若sym=0,接下来有一个非负整数p,两个整数a,b;</p>
<p>若sym=1,接下来有两个正整数a,b;</p>
<p>若sym=2,接下来有一个正整数p;</p>
<p>p、x、y的含义及范围见题目描述。</p>
<p>在任何情况下，保证序列中的元素总数不超过100000。</p>
<p>保证题目涉及的所有数在int内。</p></div>

# Output

<div class="content"><p>对每个sym=2，输出一行，包括一个整数，代表询问位置的元素。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 2 3 4 5<br/>
0 2 1 4<br/>
1 3 8<br/>
2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=From LiZitong">From LiZitong</a></p></div>

