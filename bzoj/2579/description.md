
# Description

<div class="content"><p><span style="font-size: medium"><br/>
积性函数是指具有性质f(m*n)=f(m)*(f(n)的一类函数。现在我们对一个积性函数f增加一个限制条件：如果m与n互质，则f(m)与f(n)也互质，并且一定有f(1)=1。函数f的定义域和值域都是正整数。</span></p>
<p><span style="font-size: medium">现在，你被提供了一些x以及相对应的f(x)的值。你的任务是对于每一个询问的y，判断f(y)的值是否唯一，如果唯一，输出f(y)的值。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入的第一行包含了测试点的个数。对于每一个点，第一行包含了一个整数N，这是提供的(x,f(x))的对数。接下来N行，每行的有两个被空格分开的数，第一个是x值，第二个是其对应的f(x)值。下一行是询问的个数q。下面q行每行包含了一个询问的y。</span></p>
<p></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每一个测试点输出q行，每一行对应一个询问。如果给出的数据与函数f的性质不符或者不能凭借给出的数据确定惟一的f(y)，输出”NO”，否则输出”YES f(y)”，其中的f(y)被替换成f(y)的值，不能包含前导0。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3<br/>
2 2<br/>
3 2<br/>
7 19<br/>
1<br/>
7<br/>
1<br/>
6 6<br/>
1<br/>
6<br/>
2<br/>
2 2<br/>
3 3<br/>
1<br/>
12<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">NO<br/>
YES 6<br/>
YES 12<br/>
<br/>
约束条件<br/>
<br/>
测试点的个数小于20，N&lt;=50，给出的x和f(x)都不大于10^50。x与f(x)都没有大于100005的质因数。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

