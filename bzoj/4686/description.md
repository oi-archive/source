
# Description

<div class="content"><div>Ginkgo数是指一种由整数组成的二元组(m,n)，其中m和n都是整数。例如，(1,1),(-2,1)和(-3,-1)都是Ginkgo数。</div>
<div>Ginkgo数的乘法被定义为(m,n)?(x,y)=(mx-ny,my+nx)。例如，(1,1)?(-2,1)=(-3,-1)。一个Ginkgo数(m,n)被认为</div>
<div>是一个Ginkgo数(p,q)的约数，则要存在一个Ginkgo数(x,y)使得(m,n)?(x,y)=(p,q)。对于任何的Ginkgo数(m,n)，</div>
<div>它都至少有(1,0),(0,1),(-1,0),(0,-1),(m,n),(-n,m),(-m,-n)和(n,-m)作为它的约数。当m^2+n^2&gt;1时，至少有8</div>
<div>个不同的Ginkgo数作为它的约数。一个Ginkgo数被认为是质数，则要有m^2+n^2&gt;1且它恰好含有8个不同的约数。你</div>
<div>的任务就是判断给定的Ginkgo数是不是质数。以下两个结论或许能帮助你完成上述任务：若m^2+n^2&gt;0，则(m,n)是</div>
<div>(p,q)的约数当且仅当m^2+n^2是mp+nq和mq-np的公约数。如果(m,n)?(x,y)=(p,q)，那么(m^2+n^2)(x^2+y^2)=p^2+</div>
<div>q^2。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数T，表示有T组数据。</div>
<div>每组数据占一行，包含两个整数m和n，表示一个Ginkgo数(m,n)。你可以认为1&lt;m^2+n^2&lt;20000。</div>
<p></p></div>

# Output

<div class="content"><p>对于每组数据输出一行，如果给定的Ginkgo数是质数则输出‘P’，否则输出‘C’。（不含引号）</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
10 0<br/>
0 2<br/>
-3 0<br/>
4 2<br/>
0 -13<br/>
-4 1<br/>
-2 -1<br/>
3 -1 </span></div>

# Sample Output

<div class="content"><span class="sampledata">C<br/>
C<br/>
P<br/>
C<br/>
C<br/>
P<br/>
P<br/>
C<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

