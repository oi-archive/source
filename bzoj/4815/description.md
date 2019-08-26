
# Description

<div class="content"><div>小Q是个程序员。</div>
<div>作为一个年轻的程序员，小Q总是被老C欺负，老C经常把一些麻烦的任务交给小Q来处理。每当小Q不知道如何解决</div>
<div>时，就只好向你求助。为了完成任务，小Q需要列一个表格，表格有无穷多行，无穷多列，行和列都从1开始标号。</div>
<div>为了完成任务，表格里面每个格子都填了一个整数，为了方便描述，小Q把第a行第b列的整数记为f(a,b),为了完成</div>
<div>任务，这个表格要满足一些条件：(1)对任意的正整数a,b,都要满足f(a,b)=f(b,a)；(2)对任意的正整数a,b,都要</div>
<div>满足b×f(a,a+b)=(a+b)*f(a,b)。为了完成任务，一开始表格里面的数很有规律，第a行第b列的数恰好等于a*b，</div>
<div>显然一开始是满足上述两个条件的。为了完成任务，小Q需要不断的修改表格里面的数，每当修改了一个格子的数</div>
<div>之后，为了让表格继续满足上述两个条件，小Q还需要把这次修改能够波及到的全部格子里都改为恰当的数。由于</div>
<div>某种神奇的力量驱使，已经确保了每一轮修改之后所有格子里的数仍然都是整数。为了完成任务，小Q还需要随时</div>
<div>获取前k行前k列这个有限区域内所有数的和是多少，答案可能比较大，只需要算出答案mod1,000,000,007之后的结</div>
<div>果。</div>
<p></p></div>

# Input

<div class="content"><div>第1行包含两个整数m,n,表示共有m次操作，所有操作和查询涉及到的行编号和列编号都不超过n。</div>
<div>接下来m行，每行4个整数a,b,x,k表示把第a行b列的数改成x，然后把它能够波及到的所有格子全部修改，保证修改</div>
<div>之后所有格子的数仍然都是整数，修改完成后计算前k行前k列里所有数的和。</div>
<div>1&lt;=m&lt;=10000,1&lt;=a,b,k&lt;=N&lt;=4*10^6,0&lt;=x&lt;=10^18</div>
<p></p></div>

# Output

<div class="content"><p>输出共m行，每次操作之后输出1行，表示答案mod 1,000,000,007之后的结果。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 1 1 2<br/>
2 2 4 3<br/>
1 2 4 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
36<br/>
14<br/>
<br/>
一开始,表格的前3行前3列如图中左边所示,前2次操<br/>
作后表格没有变化,第3次操作之后的表格如右边所示。<br/>
1 2 3                2 4 6<br/>
2 4 6                4 4 12<br/>
3 6 9                6 12 9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

